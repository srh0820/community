# :clipboard: 커뮤니티 프로젝트
사용자들이 게시글과 댓글을 작성하며 소통하는 커뮤니티 서비스입니다.

</br>

## 💻 사용 기술 스택
- Java jdk
- Spring boot3.0.6, Gradle
- Spring Web, Spring Security, Lombok, Thymeleaf
- JPA, MySQL
- Intellij

</br>

## 💡 프로젝트 기능
☑️ Todo
#### 회원가입
* -[ ] 회원가입시 ID, Password가 필요하다. ID는 unique 해야한다.
* -[ ] 회원가입시 모든 사용자는 일반 권한을 지닌다. 
* -[ ] 회원가입시 가입일시가 저장된다.

#### 로그인
* -[ ] 회원가입시 입력한 ID, Password가 일치해야한다. 일치하지 않는다면 에러가 발생한다.
* -[ ] 회원가입한 적이 없는 ID를 이용하여 로그인을 시도하면 에러가 발생한다.

#### 게시글 작성
* -[ ] 로그인 한 사용자만 글을 작성할 수 있다.
* -[ ] 게시글 작성시 제목, 내용을 작성할 수 있다.
* -[ ] 게시글 작성시 작성일시와 사용자의 아이디 정보가 저장(표시)된다.

#### 게시글 수정 및 삭제
* -[ ] 게시글을 작성한 사용자 본인만 수정 및 삭제가 가능하다.
* -[ ] 게시글을 수정하면 작성일시가 수정일시로 최신화된다.

#### 게시글 목록 조회
* -[ ] 로그인 여부에 관계 없이 모든 사용자는 게시글 목록을 조회할 수 있다.
* -[ ] 게시글은 최신순으로 정렬된다.

#### 게시글 조회
* -[ ] 로그인 여부에 관계 없이 모든 사용자는 게시글을 조회할 수 있다.

#### 댓글 작성 및 조회
* -[ ] 로그인 한 사용자만 댓글을 작성 및 조회할 수 있다.

#### 댓글 수정 및 삭제
* -[ ] 댓글을 작성한 사용자 본인만 수정 및 삭제가 가능하다.

#### 🌱 구현해보고 싶은 추가 기능(추후 구현)
- 게시판 카테고리 생성 및 게시글 분류 (공통된 관심사를 가진 사용자들끼리 편리하게 커뮤니티를 이용하기 위함)
- 게시글 좋아요(공감) 기능

</br>

## 🔗 ERD
<img width="1080" alt="erd" src="https://user-images.githubusercontent.com/121335941/236657541-0ea1995b-bb06-4de1-b916-d9c292917782.png">

## ✔️ [Trouble Shooting](https://github.com/srh0820/community/blob/main/Trouble_Shooting.md)
