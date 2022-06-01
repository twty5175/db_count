# 데이터 베이스 카운트
>  PHP 프로그램과 MySQL을 연동하여 카운트 된 횟수를 화면에 보여주는 프로젝트

### 작동 순서
> 미리 생성해 놓은 데이터베이스('apb_db)와 연결, (count_table)테이블 생성
> 1. 테이블에서 등록일자가 오늘인 레코드를 조회합니다.
> 2. 오늘 처움 방문인지, 기존 방문자가 있는지를 판단합니다.
> 3. 처음 방문자의 경우 총 방문자 수는 1 증가, 오늘 방문자 수는 1로 초기화됩니다. 
> 4. 기존 방문자의 경우 오늘 방문자 수와 전체 방문자 수를 1씩 증가시킵니다.
> 5. 카운트를 출력합니다.

### 실행 화면
1. db_count.php 실행화면
![image](https://user-images.githubusercontent.com/89179991/171313391-7fcfa6a6-961a-4042-8b8c-bb90c84498c1.png)


2. count_table에 저장된 방문 횟수
![image](https://user-images.githubusercontent.com/89179991/171313722-e7a4f25c-26ff-40ab-8a84-a25679b15282.png)

3. F5키 또는 [새로고침] 을 눌러 방문 횟수 증가 확인
![image](https://user-images.githubusercontent.com/89179991/171313887-a9812387-4527-4c51-820a-34c341f98ce3.png)
