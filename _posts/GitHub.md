---
layout: single
title: "GitHub 폴더 / 파일 올리는 법"
---


# **GitHub**

## 깃헙 폴더 / 파일 올리는 법

> 출처 : https://blog.naver.com/bgpoilkj/221754225086



1.  **Git Bash 프로그램 실행**

   

2.  **git config --global user.email "이메일주소"**

    **git config --global user.name "이름"** 

   

3.  **cd 폴더 주소로 이동**

   

4.  **git status 현재 상태확인**

   

5.  **git add (폴더명) or git add * (전체)**

   

6.  **git ommit -m "커밋내용"**

   

7.  **git remote add origin "자신의 git 주소"**



> **간혹 github에 올리는데 위와같이 에러가 발생하는 경우가 있는데 무조건 push한다고 해서 업로드되는것이 아니라 기존 내용을 pull가져오고 난 뒤에 push해야 합니다. 만약 강제적으로 업로드 하고 싶다면 아래와같이 하면 됩니다 git push origin +master을 입력하면 강제로 업로드가 되지만 기존에 있는 내용은 삭제됩니다.**

