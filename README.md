# 물건 찾기 서비스(Find My Stuffs) 🤔

파워 J를 위한 물건 찾기 서비스 🗄️🚪📦
<br><br>
 

### 📄 ERD
<br>
<p>
  <img width="3000px'; heiht="4500px"; src="https://github.com/user-attachments/assets/8e228e66-c72c-4eea-b770-fed2a69c0d04">
</p>
<br>

### 📄 API 정의서
###  👪 유저 API

| 기능 | HTTP 메서드 | 엔드포인트 |
|:-----|:-----------|:-----------|
| 회원가입 | POST | /users |
| 사용자 조회 | GET | /users/{userId} |
| 사용자 정보 수정 | PUT | /users/{userId} |
| 회원 비활성화 | PATCH | /users/{userId}/deactivate |
| 로그인 | POST | /users/sessions |
| 로그아웃 | DELETE | /users/sessions |


###  📚 아이템 API

| 기능 | HTTP 메서드 | 엔드포인트 |
|:-----|:-----------|:-----------|
| 카테고리 추가 | POST | /categories |
| 카테고리 수정 | PUT | /categories/{categoryId} |
| 카테고리 삭제 | DELETE | /categories/{categoryId} |
| 아이템 추가 | POST | /items |
| 아이템 조회 | GET | /items/{itemId} |
| 아이템 수정 | PUT | /items/{itemId} |
| 아이템 삭제 | DELETE | /items/{itemId} |
| 아이템 댓글 달기 | POST | /items/{itemId}/comments |
| 아이템 댓글 가져오기 | GET | /items/{itemId}/comments |
| 아이템 댓글 수정 | PUT | /items/{itemId}/comments/{commentId} |
| 아이템 댓글 삭제 | DELETE | /items/{itemId}/comments/{commentId} |
| 아이템 사진 추가 | POST | /items/{itemId}/pics |
| 아이템 사진 모두 가져오기 | GET | /items/{itemId}/pics |
| 아이템 사진 삭제 | DELETE | /items/{itemId}/pics/{picId} |

###  🗄 장소 API

| 기능 | HTTP 메서드 | 엔드포인트 |
|:-----|:-----------|:-----------|
| 장소 추가 | POST | /places |
| 장소 조회 | GET | /places/{placeId} |
| 장소 수정 | PUT | /places/{placeId} |
| 장소 삭제 | DELETE | /places/{placeId} |
| 저장장소 추가 | POST | /places/{placeId}/spaces |
| 저장장소 리스트 | GET | /places/{placeId}/spaces |
| 저장장소 조회 | GET | /places/{placeId}/spaces/{spaceId} |
| 저장장소 수정 | PUT | /places/{placeId}/spaces/{spaceId} |
| 저장장소 삭제 | DELETE | /places/{placeId}/spaces/{spaceId} |


