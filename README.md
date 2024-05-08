# Web Game Together

---

- 24-05-08 / 개발 환경 구축
  - Django Rest Framework (DRF) + React + Next.js
    - <a href="https://wikidocs.net/book/9596" target="_blank">참고자료</a>
  - 보일러플레이트 (Boilerplate)
    - 소프트웨어 개발에서 사용되는 일종의 템플릿이나 초기 코드의 집합이며, 보일러플레이트는 일반적으로 반복적이고 표준적인 작업을 빠르게 시작할 수 있도록 도와줌
    - `Builder Book` : Next.js, Material-UI, React, 그리고 Express와 같은 기술을 사용하여 사용자들에게 풀 스택 자바스크립트 애플리케이션을 구축하는 방법을 가르치는 오픈 소스 웹 애플리케이션
    - `Django-React-Next.js Boilerplate` : Django, React, 그리고 Next.js를 사용하여 풀 스택 애플리케이션을 구축하기 위한 보일러플레이트로, 이 조합을 사용하려는 개발자들에게 견고한 시작점을 제공함
    - `SaaS Boilerplate` : Django, React, 그리고 Next.js로 구축된 소프트웨어-서비스 보일러플레이트로, 개발자들이 빠르게 자신만의 SaaS 애플리케이션을 생성하고 배포하는 데 도움을 줌
  - [windows] Django 설치
    1. windows에서 가상 환경 모듈 설치하기
       - `pip install virtualenv`
    2. 프로젝트 경로로 이동하기
    3. 가상 환경 생성하기
       - `python -m venv 가상환경디렉토리명`
         - 관습적으로 `python -m venv env`를 사용함
    4. 가상 환경 활성화하기
       - `가상환경디렉토리명/Scripts/activate`
       - 특별한 상황이 아니라면 항상 Python 프로젝트 가상 환경에서 실행하기
       - 가상 환경 종료 : `deactivate`
    5. 프로젝트에 Django를 설치하기
       - `pip install django`
       - 설치 후, `django-admin --version`을 입력해 설치 확인하기
    6. Django 프로젝트 생성하기
       - `django-admin startproject 장고프로젝트명`
         - ex. `django-admin startproject backend`
    7. 장고프로젝트로 이동 후, 개발 서버 실행하기
       - `python manage.py runserver`
       - ex.
         ```
         cd backend
         python manage.py runserver
         ```
    8. `http://127.0.0.1:8000`을 방문하여, 프로젝트 동작 확인하기
       - 서버 종료 : `Ctrl + C`
    - <a href="https://youtu.be/nNwMTI0-E7s?list=PLgnySyq8qZmru0pXm7Bsj3BHpzDExNITU" target="_blank">참고영상</a>
    - <a href="https://wikidocs.net/197533" target="_blank">참고자료</a>
  - [Windows] Django 서버 실행
    1. 가상 환경 실행하기
       - `가상환경디렉토리명/Scripts/activate`
       - 가상 환경 종료 : `deactivate`
    2. 개발 서버 실행하기
       - 장고프로젝트로 이동 후, `python manage.py runserver`
       - 서버 종료 : `Ctrl + C`

---

TODO

- Django의 키값을 .env 파일을 사용하기
- Django REST Framework (DRF) 설치하기
  - https://wikidocs.net/197533#hello-world
