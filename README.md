# som-react-calendar

리액트 기반 캘린더 입니다

## 기능

| parameter     | description                                                   | default value | example                               |
| ------------- | ------------------------------------------------------------- | ------------- | ------------------------------------- |
| `onClickDate` | 선택한 날짜를 처리할 함수                                     | none          | `onClickDate={(d) => console.log(d)}` |
| `startDate`   | 캘린더에 표시할 시작하는 날짜 (시작하는 날짜 이전엔 비활성화) | none          | `startDate=new Date()`                |
| `endDate`     | 캘린더에 표시할 끝나는 날짜 (끝나는 날짜 이후엔 비활성화)     | none          | `endDate=new Date()`                  |
| `defaultView` | 디폴트 설정할 뷰(week, month)                                 | week          | `defaultView='month'`                 |

## preview

### week view


![image](https://user-images.githubusercontent.com/60869490/145761860-9d1c183f-42c4-4057-b033-0eb348f60403.png)

### month view


![image](https://user-images.githubusercontent.com/60869490/145761934-4fffafc4-ee23-4351-b214-56afb2f19e67.png)
