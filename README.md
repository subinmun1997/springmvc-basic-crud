# Item Service CURD 

## 요구사항 분석

1. 상품 도메인 모델
  * 상품 ID
  * 상품명
  * 가격
  * 수량

2. 상품 관리 기능
  * 상품 목록
  * 상품 상세
  * 상품 등록
  * 상품 수정
 
## 서비스 화면

1. 상품 목록

![image](https://user-images.githubusercontent.com/52366841/156705095-dce9452e-d900-4433-ab89-8484184ea882.png)


2. 상품 상세

![image](https://user-images.githubusercontent.com/52366841/156705154-555e549f-a437-4807-ab86-cc6437667a2f.png)


3. 상품 등록 폼

![image](https://user-images.githubusercontent.com/52366841/156705229-bee5760b-8742-40b1-9fe1-7a4712cc7dd1.png)


4. 상품 수정 폼

![image](https://user-images.githubusercontent.com/52366841/156705273-77900fbb-f2a2-4a45-bda3-5bd3ee3b7852.png)


# 서비스 제공 흐름

![image](https://user-images.githubusercontent.com/52366841/156705327-c63fc971-1f8e-4d6e-bdde-73127332172e.png)


# ✨ Refactoring

### v1 - Form

#### 요구사항 추가

3. 판매 여부
  * 판매 오픈 여부
  * 체크 박스로 선택할 수 있다.

4. 등록 지역
  * 서울, 부산, 제주
  * 체크 박스로 다중 선택할 수 있다.

5. 상품 종류
  * 도서, 식품, 기타
  * 라디오 버튼으로 하나만 선택할 수 있다.

6. 배송 방식
  * 빠른 배송
  * 일반 배송
  * 느린 배송
  * 셀렉트 박스로 하나만 선택할 수 있다.

## 서비스 화면

5. 요구사항 추가 폼

![image](https://user-images.githubusercontent.com/52366841/157388217-c5fa282e-57d4-4b74-bcdd-cb8212ca99a6.png)


## Refactoring v1 - 결과물

1. 상품 목록

![image](https://user-images.githubusercontent.com/52366841/157588809-be02026f-eb12-483d-bc3d-ad2547615600.png)

2. 상품 상세

![image](https://user-images.githubusercontent.com/52366841/157588903-293a82ff-3b4e-443e-b4cb-339e544ec5e9.png)


3. 상품 등록 폼

![image](https://user-images.githubusercontent.com/52366841/157588873-c173c418-e025-47f9-ae96-3e91df95697c.png)


4. 상품 수정 폼

![image](https://user-images.githubusercontent.com/52366841/157588931-ada68502-4c78-477f-a9a4-cc33a098b2e4.png)


# ✨ Refactoring

### v2 - Message

#### 요구사항 추가

7. 메시지 관리
  * 다양한 메시지를 한 곳에서 관리하도록 하는 기능 추가

8. 국제화 (Internationalization)
  * 메시지 파일을 각 나라별로 별도로 관리해서 서비스를 국제화 하는 기능 추가


## Refactoring v2 - 결과물

1. 상품 목록

![image](https://user-images.githubusercontent.com/52366841/158136174-1f075f8a-a7ec-4dca-acb7-720ddc36b238.png)

2. 상품 상세

![image](https://user-images.githubusercontent.com/52366841/158136090-f5322cfc-cb79-4493-b5db-de96dd849e0c.png)


3. 상품 등록 폼

![image](https://user-images.githubusercontent.com/52366841/158136234-9795eb41-80fd-4d64-8169-161aa20c77cb.png)


4. 상품 수정 폼

![image](https://user-images.githubusercontent.com/52366841/158136301-4747d1a8-aaf4-4b92-ad6b-131c6673f35f.png)


# ✨ Refactoring

### v3 - Validation

#### 요구사항 추가

9. 검증 로직 추가
  * 타입 검증
   * 가격, 수량에 문자가 들어가면 검증 오류 처리
  * 필드 검증
   * 상품명: 필수, 공백X
   * 가격: 1000원 이상, 1백만원 이하
   * 수량: 최대 9999개
  * 특정 필드의 범위를 넘어서는 검증
   * 가격 x 수량의 합은 10,000원 이상


# 서비스 제공 흐름
![image](https://user-images.githubusercontent.com/52366841/158320006-13399650-d558-450b-9379-86205a2cb9fc.png)


## Refactoring v3 - 결과물

1. 상품 등록

![image](https://user-images.githubusercontent.com/52366841/158320280-7a8d1837-1831-46e1-9560-eed8d4155245.png)

![image](https://user-images.githubusercontent.com/52366841/158320314-9f807476-3b8c-4a4a-bd8a-b1ed1d0ee078.png)




