# doctorbixby.doctorbixby 팀 공지사항

사전절차
1. 각자 이메일 DoctorBixby 초대 확인
2. https://bixbydevelopers.com/ 접속
3. 회원가입 & Bixby Developer Studio 다운로드
4. 삼성 아이디 김민철한테 전송
5. Bixby Developer Studio 실행 > 로그인> create New Capsule > "example.dfsfd" 생성


깃 저장소 생성법
1. c > 사용자 > student > bixby-workspace
2. 폴더안엔서 우클릭 git bash 실행
3. git bash 안에서 git init 실행
4. git config --global user.name "유저이름"
5. git config --global user.email "메일"
6. git clone https://github.com/mincheol6073/doctorbixby.doctorbixby.git
7. git remote add origin https://github.com/mincheol6073/doctorbixby.doctorbixby.git
8. git branch 브랜치명
9. git checkout 브랜치명

깃 내용 업데이트하는법
1. git status // 변경내용 확인
2. git add 파일명 // 전체를 업로드 할경우 보통 파일명에 * 를씀
3. git commit -m '업데이트 내용' // 업데이트 내용으로 commit (프로그램 리턴 분기점이기 때문에 내용 꼭 작성)
4. git push -u origin 브랜치명

병합하는 방법
1. git checkout 팀명 // 팀명 branch로 이동
2. git merge 자신 // 자신의 branch로 부터 merge 작업 수행
ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ충돌 발생시 ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
3. 충돌이 생길시 충돌 해결 후
4. git add * > git commit -m '충돌해결 내용' > git push -u origin 팀명

etc / 기타 궁금한 사항들은 김민철한테 물어보기
git pull : 서버와 동기화
git reset : 작업 실행취소
git rm --cache 폴더 : 원격저장소 디렉터삭제
