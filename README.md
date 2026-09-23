# book_rating

> 도서 데이터 분석 및 평점 모델 실험

## 프로젝트 개요

- 주제: 도서 데이터 분석 및 평점 모델 실험
- 형태: Jupyter Notebook 기반 실험
- 저장소: https://github.com/ttony0321/book_rating
- 기본 브랜치: main
- 공개 범위: Public

## 주요 기능

- 도서 데이터 EDA
- 평점 데이터 분석
- 모델 실험 Notebook 분리
- SVD()모델 사용
- GridSearchCV 사용하여 파라미터 설정후 nfold 적용하여 학습 


## 기술 스택

- Python
- Jupyter Notebook

## 프로젝트 구조

- `README.md`
- `book_EDA.ipynb`
- `book_rating.ipynb`

## 실행 방법

- Jupyter 실행 환경 구성
- 데이터 경로 설정
- 실행 순서: book_EDA.ipynb → book_rating.ipynb

## 핵심 구현

- 분석 과정과 모델 실험을 Notebook 단위로 분리
- 데이터 탐색부터 결과 확인까지의 흐름 구성

## 개선 과제

- 의존성 버전 고정
- 환경변수 기반 경로·설정 관리
- 대표 평가 지표와 결과 그래프 문서화

