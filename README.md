# Calendar_Notification
공유캘린더 Notification 개발 경험 정리
![image](https://github.com/mr-won/Calendar_Notification/assets/58906858/99708e4d-73de-41ff-b7c6-f4d240f126e7)
```
일정을 입력할 때의 시작일과 현재 날짜가 같으면 알림을 띄우는 서비스를 개발하고자 한다.
기존 Android가 제공하는 Notification 기능을 사용하였다.

사용자시나리오는 사용자가 일정에 coding 시작일에 2023-11-20 넣으면
```
## 오늘 날짜와 일정 시작일을 비교하여 NotiPlay()함수를 호출하는 로직
![image](https://github.com/mr-won/Calendar_Notification/assets/58906858/3175381f-9366-4f58-8612-f9c09136f26f)    
![image](https://github.com/mr-won/Calendar_Notification/assets/58906858/508dfa6d-5d26-4313-a2ef-6c52fb761ff5)    
```
오늘 날짜와 일정 시작일이 같으면 해당하는 notiList의 startDate와 Plan, startTime 데이터를 가공하여 알림을 호출하도록 한다.
```
