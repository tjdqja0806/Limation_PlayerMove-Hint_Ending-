Project 1 : Limation

PlayerMove(Hint and Ending) system Script

Explanation
1. Input 함수를 이용하여 플레이어의 위치를 이동, SubMunu 호출, 카메라의 각도 변환 등의 기능
2. OnTriggerEnter 함수를 사용하여 스토리 진행 버튼 활성화
3. ScreenPointToRay함수를 이용하여 마우스의 클릭 위치를 Ray로 파악하고 그 위치에 해당 오브젝트가 있다면 힌트 활성화(ESC키를 통해 비활성화)
4. Coroutine 함수를 사용하여 자연스러운 Engind 기능 생성

Game Scene

![힌트](https://user-images.githubusercontent.com/74092254/99870757-eb182f00-2c18-11eb-8686-e9f93e2a76c6.png)

![엔딩](https://user-images.githubusercontent.com/74092254/99870777-04b97680-2c19-11eb-99aa-c3c323092eb2.png)
