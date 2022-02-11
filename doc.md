##step 1: 

     "git init"

-> declare repository in local: (repository will contains code)
----------------------------------------------------------------
##step 2': (unnecessary)
     
     "git status"

-> view status of repository
----------------------------------------------------------------
##step 2: 

     "git checkout -b develop"  ----- has \-b\
     ->   create a new branch with optional name, in this case
          is "develop" and switch to that branch at the same time

     "git checkout develop" ----- hasn't \-b\
     -> switch to optional branch, in this case is "develop"

~ trong thực tế, dự án sẽ được chia thành nhiều task
khác nhau, mỗi task tương ứng với một branch. ai được giao
task nào sẽ thực hiện cập nhật tiến độ trên branch đó,
khiến cho việc quản lí code trở nên dễ dàng hơn.
----------------------------------------------------------------
#COMMIT CODE:  
##step 3: 
     
     "git add fileName"
          ~ add file chỉ định

     "git add ."
          ~ add tất cả các file cùng lúc

----------------------------------------------------------------

##step 4: git commit -m "commit's description"
-> Description for this commit
----------------------------------------------------------------
##step 5: git remote add origin repository-URL
-> add remote
----------------------------------------------------------------
##step 6: git push origin develop
push source code upto git
