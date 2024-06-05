<div align="center">
    <img src="./final-pjt-front/public/assets/logo.png" alt="Logo" width="80" height="80">

  <h3 align="center">THE FP</h3>

  <p align="center">
    <h3><a href="https://thefp-bcw8u4ic8-coolfins-projects.vercel.app/">서비스 바로가기</a></h3>
  </p>
</div>

<br/>
<br/>
<br/>

### THE FP

---

금융상품 정보를 분류하고 사용자에게 금융상품을 추천해주는 프로젝트입니다. 환율 계산, 주변은행 등의 정보를 추가로 제공합니다.
<br/>
<br/>
<br/>

### Stacks

---

> FE

**언어**

<div style="display:flex; margin-bottom:20px;">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">
</div>

**라이브러리**

<div style="display:flex; flex-wrap:wrap; margin-bottom:20px;">

<img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white">

<img src="https://img.shields.io/badge/pinia-000?style=for-the-badge&logo=Vue.js&logoColor=white">

<img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white">

<img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">

<img src="https://img.shields.io/badge/chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white">

<img src="https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=white">

<img src="https://img.shields.io/badge/navermaps-03C75A?style=for-the-badge&logo=naver&logoColor=white">

</div>

> BE

**언어**

<div style="display:flex; margin-bottom:20px;">
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
</div>

**라이브러리**

<div style="display:flex; flex-wrap:wrap; margin-bottom:20px;">

<img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white">

<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">


</div>

> 공통

**설계 및 환경**

<div style="display:flex; margin-bottom:20px;">

<img src="https://img.shields.io/badge/VS CODE-007ACC?style=for-the-badge&logo=html5&logoColor=white">

<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">

<img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">

</div>

<br/>
<br/>
<br/>

### 실행방법

---

FE

```py
# 1. dependencies 설치
npm i

# 2. 실행
npm run dev
```

BE

```py
# 1. 가상환경 생성
python -m venv venv

# 2. 의존성 패키지 설치
pip isntall -r requirements.txt

# 3. DB 마이그레이션
python manage.py makemigrations
python manage.py migrate

# 4. 서버 실행
python manage.py runserver
```

<br/>
<br/>
<br/>

### 🔗 [ERD](https://www.erdcloud.com/d/GbegwswkZ6pTm9tzK)

<img src='./final-pjt-front/public/assets/md/erd.png' alt="login" width="100%" />

---

<br/>
<br/>
<br/>

### 디자인

<img src='./final-pjt-front/public/assets/md/figma.png' alt="findpw" width="100%" />

모든 페이지를 구성하며 세부사항은 다르지만 전체적인 틀이 같아 기능구현 이전에 개발하기 매우 수월했습니다.

---

<br/>
<br/>
<br/>

### 서비스 대표 기능

---

> 로그인
> <img src='./final-pjt-front/public/assets/md/login.png' alt="login" width="100%" />

> 회원가입
> <img src='./final-pjt-front/public/assets/md/signup.png' alt="signup" width="100%" />

> 비밀번호 찾기
> <img src='./final-pjt-front/public/assets/md/findpw-1.png' alt="findpw" width="100%" /> > <img src='./final-pjt-front/public/assets/md/findpw-2.png' alt="findpw" width="100%" />

> 전체 금융상품 조회
> <img src='./final-pjt-front/public/assets/md/info.png' alt="info" width="100%" />

> 금융상품 상세조회
> <img src='../final-pjt-front/public/assets/md/info-detail-1.png' alt="detail" width="100%" /> > <img src='./final-pjt-front/public/assets/md/info-detail-2.png' alt="detail" width="100%" />

> 환율
> <img src='./final-pjt-front/public/assets/md/exchange.png' alt="login" width="100%" />

> 주변은행 지도
> <img src='./final-pjt-front/public/assets/md/bankmap.png' alt="login" width="100%" />

> 프로필
> <img src='./final-pjt-front/public/assets/md/profile.png' alt="login" width="100%" />

> 상품추천
> <img src='./final-pjt-front/public/assets/md/recommend.png' alt="login" width="100%" />

<br/>
<br/>
<br/>

### 상품 추천 알고리즘

상품의 pk값을 target으로 고객의 개인정보에 적합한 상품을 추천해주는 로지스틱 회귀 모델을 개발했습니다.
상품, 옵션별로 데이터를 자세하게 나누어 1000명의 user에 대해 25000개의 상품 별 개인정보 데이터를 가지고 train, test 나누어 모델 학습 진행하고 이를 보여줍니다.

---

<br/>
<br/>
<br/>

### 🔗 [후기](https://coolfin.notion.site/408d7cf7eadb4ecf9bb1c8c4d362e1ef?pvs=4)

---

<br/>
<br/>
<br/>

### Contributors

---

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/coolfin">
        <img src="https://avatars.githubusercontent.com/u/56531884?v=4" width="110px;" alt=""/><br />
        <sub><b>박상우</b></sub></a><br />
        <sub><b>FE / DESIGN / PM</b></sub></a><br />
	<sub><b></b></sub></a>
    </td>
    <td align="center">
      <a href="https://github.com/yoonkyungseo">
        <img src="https://avatars.githubusercontent.com/u/97039526?v=4" width="110px;" alt=""/><br />
        <sub><b>윤경서</b></sub></a><br />
        <sub><b>BE / ML</b></sub></a><br />
    </td>

  </tr>
</table>
