### 코딩모르는 독수리 타법 소유자지만
## GitHub Copilot의 은총으로
# [ " Word 문서 생성 자동화 " 마스터가 됐습니다  🤟 ]


<br>  
<br>  

> ### 코딩을 잘 모르신다고요?  괜찮습니다.
> ### 코딩을 잘 못한다고요?  괜찮습니다.
> ### 코딩을 잘 하신다고요?  더 효율적으로 코딩할 수 있는 방법이 있습니다.
<br>  <br>  
 

👉 바로 **GitHub Copilot**을 사용하면 되는데요.
<br>  <br>  

## < GitHub Copilot : 코딩 전문 AI >  
  
## 특성 :  

작성 중인 코드를 AI가 이해하여 다음 코드를 먼저 제시해주는 아주 **똑똑한 AI** 입니다.  
또한 ChatGPT에게 묻는 것처럼 코드에 관해서 자유롭게 궁금한 것들을 질문하면 답변을 받을 수 있습니다.

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/3834d6fa-ef59-4cc4-88f8-1077103137b8)
  
<br>  <br>  

## 사용 방법 :  

1. 코딩을 할 수 있는 도구 **VSCode**를 실행합니다.
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/f8b3f203-dde0-4d19-87a8-428edc236996)
  
2. 확장 메뉴에서 **GitHub Copilot**을 설치 버튼을 눌러 설치합니다.

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/1b8e09a5-a63a-4b20-94f3-4350b4b0c7c1)  

<br>  <br>  

<br>  <br>  

**축하합니다.  🎉🎉 
위 가이드를 따라 하셨다면, GitHub Copilot을 사용할 준비를 완료하신 겁니다.**  
**Word 문서 자동 생성 단계를 도전해 보세요.**  

<br>  <br>  
### ⚠️ 퀘스트 발생 ⚠️  
  
**당신은 소규모 쇼핑몰을 운영자로 빙의했습니다. 상품을 주문한 고객들에게 상품을 발송해야 합니다.**  
**상품을 발송할 때 주문정보를 담은 종이를 함께 발송해야 합니다.**  

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/fd3e5165-88e9-4d75-a3ac-d73878049540)

**상품 주문 정보가 다음과 같이 제공됩니다.**  
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/8991c4d6-de66-4a62-91f8-c19779b7ac5e)

  
  
## 🔔 퀘스트 : 
## 주문자별 "주문정보종이"를 빠르게 생성할 수 있도록 
## [ Word 문서 작성 자동화 코드 ]를 만드시오.

<br>  <br> 
<br>  <br>   
  
# 😰😰  
어떻게 해야할지 막막합니다. 하지만 저희에게는 **GitHub Copilot**이 있으니 함께 도전합시다.
<br>  <br>  

### 1. VSCode를 연 후, 파일>새파일>Python 파일을 클릭해 새 Pyhthon 파일을 만듭니다.   
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/c828bb56-b951-4bdb-975e-1d30e71aff5f)  
<br>  
  
### 2. Ctrl+I 버튼을 눌러 GitHub Copilot을 호출합니다.  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/21181b97-64aa-454a-81c6-91897250c2e5)  
  <br>  
GitHub Copilot한테  ```csv 파일을 불러와```라고 시킵니다.  
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/fc7e5786-663f-4ed1-b447-1fbb7be3fd7f)

GitHub Copilot이 생성한 코드를 **수락**합니다.

### 3. 아래 링크에서 주문정보를 다운받습니다.  
  
[주문정보파일](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/blob/main/info.csv)

    
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/ccf9cd53-817b-4dc3-b1ee-b5d0d2cc9f6a)

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/6110ede4-387f-4226-965e-b7efb2dedce0)  

다운받은 파일에 마우스를 올린 후, 우클릭을 하면 "경로복사"가 뜹니다. 경로를 복사해  
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/35040584-f523-47fd-b52b-0a74b99ca8f2)  
  
해당 부분의 내용을 변경합니다.   

```
#예시 
csv_file="C:\\Users\\hello\\Desktop\\info.csv"
```
<br>  <br>  

### 4. Ctrl+I를 다시 누른 후, GitHub Copilot한테 word파일을 생성하게 합니다.  

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/56138813-f87a-45e2-a1fc-a0918c179e1d)  
  
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/83106af9-5585-464f-8f83-bf129298320a)  
  
GitHub Copilot이 만든 코드를 수락하고, python 코드를 실행합니다.  

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/440f9aff-4e2b-4805-adf0-d7205b750a93)  

output.docx 워드 파일을 열어, 파이썬 코드가 잘 실행됐는지 확인합니다.  

 <br>    
  
### 5. doc~ 코드 뒤 V 부분에 마우스를 클릭합니다.   

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/85e70b59-d16f-4cd5-9d55-7cdd74cfba95)  

v에 커서가 위치하게 되는데,   
```#안녕하세요 고객님을 워드에 적기```를 적은뒤 엔터를 누릅니다.  
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/fd447614-6e24-4630-b518-70258d2b879f)   

그러면  ✨ 이모티콘이 뜨면서 회색글자들이 나타납니다. ```Tab```버튼을 누르면 회색글자가 입력됩니다. **Tab 버튼**을 누르십시오.  
<br>
  
그 다음, ```#무슨무슨 고객님 무슨무슨 제품을 구매해주셔서 감사합니다.```를 적은 뒤 엔터를 누릅니다.  
Tab 버튼을 클릭해 자동생성된 회색 코드를 수락합니다.  
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/062dc3ce-5127-494f-8b59-c3069dd9c837)


```#고객님의 주문 정보는 다음과 같습니다.```를 입력 후, Tab 버튼을 클릭해 자동생성된 회색 코드를 수락합니다.  
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/0406c0c3-5e5d-4960-9489-3fa54010d524)  

<br>  <br>  

파이썬 코드를 실행해 잘 동작하는지 확인합니다.  
코드를 실행 후, output.docx를 열어 확인합니다.  
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/3095cbfe-e28f-4477-b374-5b3d76b19569)  

  <br>  <br>  

**현재까지의 코드입니다**
```
import pandas as pd
from docx import Document

# CSV 파일 경로
file_path = "C:\\Users\\parkm\\Desktop\\info.csv"

# CSV 파일 불러오기
data = pd.read_csv(file_path)

# 데이터 확인
print(data.head())


# Word 파일 경로
file_path = "C:\\Users\\parkm\\Desktop\\hello.docx"

# Word 문서 생성
doc = Document()

#안녕하세요 고객님을 한글에 적기
doc.add_paragraph("안녕하세요 고객님")

#무슨무슨 고객님 무슨무슨 제품을 구매해주셔서 감사합니다.
doc.add_paragraph("무슨무슨 고객님 무슨무슨 제품을 구매해주셔서 감사합니다.")

#고객님의 주문 정보는 다음과 같습니다.
doc.add_paragraph("고객님의 주문 정보는 다음과 같습니다.")


# 텍스트 추가
doc.add_paragraph("hello")

# 문서 저장
doc.save(file_path)
```

<br>  <br>  
  


### 6. csv 파일 일부를 복사해 구체적으로 Copilot에게 질문합니다.  

**#텍스트추가**문구 위 부분에 마우스를 클릭해, 커서를 위치시킨 후 Ctrl+I를 눌러 Copilot에 질문합니다.
```
VV 마우스 위치해 주세요.
# 텍스트 추가
doc.add_paragraph("hello")
```
  
```
상품명,주문번호,송장번호,고객이름,우편번호,세부주소,주문일
나뭇잎,1,68640-4032-5555,김개미,44951,허리도 가늘군 만지면 부서지리,2024-04-12
금전,2,62640-3032-5455,홍길동,22264,서울시 강남구 서초동 12길, 2024-04-30
캣닢,3,12350-2222-6412,강아지,31226,경기도 고양시 귀엽군, 2024-05-10

Csv 파일의 헤더랑 첫번째 행의 내용으로 표를 만들어 보여주고 싶어. 그런데 주문번호만 표에 넣지마.
상품명 | 고객이름 | 송장번호 | 우편번호….
나뭇잎 | 65640-4032-5555 | 김개미 | 44951 ....이런식으로 
```

csv 파일 일부를 복사해 구체적으로 Copilot에게 질문합니다.  

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/cafa9ffa-c343-4f12-88f1-d33eab1d862d)  

수락합니다.  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/8b423901-340a-4c2a-b757-460bd0478d54)  
  
```#세부주소, 주문일도 추가```를 입력한 후,
Tab, Enter, Tab, Enter를 반복해 세부주소와 주문일에 대해서도 처리할 수 있게 합니다.  

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/e78a7ae6-d98e-42b6-9430-78637f57941c)  

코드를 실행합니다.  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/097ba022-a869-433f-83c1-3c46aa45e8e7)  

  코드에 오류가 있습니다.
<br>  <br>  

### 7. 왼쪽 배너의 대화 모양 버튼을 클릭한 후, 대화창에서 GitHub Copilot에게 질문합니다.   
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/a472084d-5673-4f21-bca4-394b6d683045)  

오류에 대한 내용을 복사해 질문합니다.    
```Traceback (most recent call last):
  File "c:\Users\parkm\OneDrive\바탕 화면\just.py", line 44, in <module>
    row_cells[3].text = row['우편번호']
    ^^^^^^^^^^^^^^^^^
  File "c:\Users\parkm\AppData\Local\Programs\Python\Python311\Lib\site-packages\docx\table.py", line 284, in text
    r.text = text
    ^^^^^^
  File "c:\Users\parkm\AppData\Local\Programs\Python\Python311\Lib\site-packages\docx\oxml\text\run.py", line 129, in text
    _RunContentAppender.append_to_run_from_text(self, text)
  File "c:\Users\parkm\AppData\Local\Programs\Python\Python311\Lib\site-packages\docx\oxml\text\run.py", line 248, in append_to_run_from_text
    appender.add_text(text)
  File "c:\Users\parkm\AppData\Local\Programs\Python\Python311\Lib\site-packages\docx\oxml\text\run.py", line 252, in add_text
    for char in text:
TypeError: 'int' object is not iterable
```
  
![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/699df696-1e33-470b-8b20-f79e48a1c034)

![image](https://github.com/pmj-chosim/GitHub_Copilot-_Word-_-/assets/114579651/c437adfc-2d8a-4e82-9e59-65044ef38f89)  

Copilot의 답변에 따라 코드를 수정합니다.  
  




