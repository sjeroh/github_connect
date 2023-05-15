# github_connect

## 1. 🍎 [깃설치](https://git-scm.com/download/win)


       git을 통해서 github과 연결할 수 있다.

 - git에 올려야할 폴더에 가서 shift+우클릭 --> powershell 클릭 열기
 
  
        git init 입력 -->(하다 잘못되면 깃 초기화 방법 또한 같다.)
      
      
 - .git 폴더가 생성됨.
------------------------

## 2. :accessibility: 깃 설치 후 git bash 열기

![image](https://user-images.githubusercontent.com/36749506/235417896-a0683612-ffa5-41d5-910a-32a8b928077a.png)

![image](https://user-images.githubusercontent.com/36749506/235418053-578c219a-51f7-4da0-9497-eb2c923b360a.png)

 * 유저이름 설정

              $ git config --global user.name"sj" -->"안의 이름은 내가 마음대로"
              
 * 유저 이메일 설정하기(반드시 github에 가입했던 이메일주소와 동일해야한다.)

              git config --global user.email "your_email"
              
              깃과의 이메일을 맞춰서 "" 안을 작성
              
 * 내 정보 확인하기


              git config --list
              
              
## ⬆️ 위의 연결은 해당 컴퓨터에서 한번만 실행하면 됨.


# github에 코드 업로드하기

       * 초기화
            git init
        
       * 추가할 파일(폴더안에 내용을 모두 올림, .은 모든 파일을 의미) 
            git add .
            한칸 띄우고 점찍기
            
       * 히스토리 만들기(-m 은 메세지를 의미함 ""안에는 히스토리 이름을 적음)
            git commit -m "first commit(작업 올리기 등 내가 확인할 텍스트 히스토리 이름)"
            
       * Github의 repository를 만들고 그 주소와 연결하기
            git remote add origin https://github.com/my_user_name/my_new_git_folder.git
            
       * 연결이 잘 됐는지 확인하기(꼭 확인 할 필요는 없다)
            git remote -v (버전을 확인한다.)
            
       * Github에 올리기
            git push origin master
            
------------------------------------------------------------------

## 수정하여 다시 업로드 할때

1. 기존의 코드를 다운받는 행위를 해야한다.(반드시)
 
       git pull origin master
       실행
       
2. 다시 push 해야한다.

       git push origin master

--------------------------------------------

# Github 협업하는 방법

## 사원입장 -------------------------------
1. 소스코드 다운로드

          git clone 주소
   ![image](https://github.com/sjeroh/github_connect/assets/36749506/7f01b2c4-4f99-4697-ae77-c1f978202064)


          git clone https://github.com/sjeroh/hanacard_webprt.git (ex)
   
2. 브랜치(branch) 만들기

   "새 가지가 만들어졌다.."
   
          git checkout -b 브랜치이름
          git checkout -b "roh" (""안은 이름이나 적고자하는것)

![image](https://github.com/sjeroh/github_connect/assets/36749506/0cc5c509-361c-411f-bb67-a398e2fd0e0f)

          git add .
          git commit -m "text"
          
          git push origin 브랜치이름
          git push origin 이름

![image](https://github.com/sjeroh/github_connect/assets/36749506/ee407e51-804d-43e9-a614-98f08f72fab3)
위와 같이 가지가 생긴다.

#### 



#####



######
