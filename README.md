# 작성 규칙

<br />

① 제목(type), 본문(body), 꼬리말(footer)로 구성합니다.<br />
② 제목(type)에는 중요도에 따라 [gitmoji](https://gitmoji.dev/)를 1~3개 사용합니다.<br />
③ 각 부분은 줄바꿈으로 구분합니다.<br />

**ex)**<br />
**Feat :art:: TodoController create 기능 구현**

Body: create(what)는 사용자가 게시글을 작성하기 위해(why) 사용하는 메서드입니다.

create는 (how) FE 서버에서 사용자가 값을 입력하면 이를 감지하고 서버에 저장합니다.(e.target.value)<br />
이후 fetch()메서드를 사용하여 BE 서버로 해당 값을 전달합니다.<br />
BE 서버는 전달 받은 값을 파라미터로 해당 메서드에 전달합니다.<br />
최종적으로 DB에 저장됩니다.<br />

Fixes : #40 Related to: #29, #30

<br />

## 제목(type) 작성하기

type | description |
|--|--|
 |Feat 🎨| 새로운 기능 추가 |
 |Fix 🚑| 버그 수정 |
 |HOTFIX :fire:| 치명적 버그 수정 |
 |Comment :bookmark:| 주석 수정 |
 |Docs 📝| 문서 수정 |
 |Design 💄| 디자인 변경 |
 |Style :pencil2:| 사소한 코드 변경 |
 |BREAKING :zap:| 커다란 API 변경 |
 |Refactor 🔨| 리팩토링 |
 |Depend :heavy_plus_sign:| 의존성 추가 |
 |Depend :heavy_minus_sign:| 의존성 삭제 |
 |Test :white_check_mark:| 테스트 작업 |
 |Rename :card_file_box:| 파일, 폴더명 수정 |
 |Move :truck:| 파일, 폴더 경로 변경 |
 |Remove :wastebasket:| 파일 삭제 |
 |Chore :technologist:| 기타 사소한 작업 |
 |Conf 🔧:| 설정 파일 작업 |
 
 
**ex)**<br />
Feat 🎨: TodoController create 기능 구현

<br />

## 본문(body) 작성하기

① 자세히 작성합니다.<br />
② 무엇을(what) 왜(why)를 중심으로 작성합니다.<br />
③ 한 줄당 72자가 넘지 않도록 합니다.<br />

**ex)**<br />
Body: create는 사용자가 게시글을 작성하기 위해 사용하는 메서드입니다.<br />

create는 FE 서버에서 사용자가 값을 입력하면 이를 감지하고 서버에 저장합니다.(e.target.value)<br />
이후 fetch()메서드를 사용하여 BE 서버로 해당 값을 전달합니다.<br />
BE 서버는 전달 받은 값을 파라미터로 해당 메서드에 전달합니다.<br />
최종적으로 DB에 저장됩니다.

<br />


## 꼬리말(footer) 작성하기

① 꼬리말은 선택사항(optional)입니다.<br />
② 이슈 트래커 ID를 작성합니다.<br />
③ 여러 개의 이슈 번호는 쉼표로 구분합니다.<br />

<br />

### 이슈 트래커 유형

Fixes : 이슈 수정 중<br />
Resolves : 이슈 해결<br />
Ref :thread : 참고할 이슈<br />
Related to : 해당 커밋에 관련된 커밋 번호<br />

**ex)**<br />
Fixes : #40 Related to: #29, #30
 
 
 
<br />
