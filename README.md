# Работа с git и bash

# bash1.txt - Задача 1
1. cd ~
2. pwd
3. mkdir test1
4. cd test1
5. touch 1 2 3
6. ls
7. cd ~
8. mkdir test2
9. rmdir test2
10. rm ~/test1/2
11. mkdir ~/test3
12. rm -r ~/test3
13. mkdir ~/test4
14. mv ~/test1/1 ~/test1/3 ~/test4
15. echo -e "line\nline\nline" ~/test4/1
16. cat ~/test4/1
17. echo -e "line\nline\nline" >> ~/test4/3
18. cat ~/test4/1 ~/test4/3
19. nano ~/test4/1
    

# bash1.txt - Задача 2
1. cd ~
2. mkdir test3
3. echo -e "row1\nrow2\nrow3\nrow4" > ~/test3/4
echo -e "row1\nrow2\nrow3\nrow4" > ~/test3/5
echo -e "row1\nrow2\nrow3\nrow4" > ~/test3/6
4. grep "row2" ~/test3/5
5. grep "row" ~/test3/*
6. grep -c "row" ~/test3/6
7. find ~/test3 -name 5
8. find ~/test3 -name 5 -delete
9. echo "test" > ~/test3/4
10. sed -i 's/test/fail/g' ~/test3/4
11. echo "test" >> ~/test3/4
12. ps -ef
13. kill 666
14. ping rusau.net
15. ping -c 5 rusau.net
16. curl -X GET "https://petstore.swagger.io/v2/pet/findByStatus?status=available"
17. curl -X POST "https://petstore.swagger.io/v2/user" \
  -H "Content-Type: application/json" \
  -d '{"id":1,"username":"testuser","firstName":"John","lastName":"Doe","email":"john@example.com","password":"1234","phone":"123456","userStatus":1}'
