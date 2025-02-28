#WIL #본캠프  [[본캠프]]
## 1. FACTS (이번 주 동안 있었던 일, 내가 한 일)
1. Django 프로젝트 개발:
    - Django와 Django REST Framework(DRF)를 활용하여 웹 애플리케이션 및 API 설계 실습.
    - `APIView`, `Serializer`, `ForeignKey` 등을 활용하여 CRUD 기능 구현.
    - 데이터베이스 모델링과 `unique_together` 제약 조건을 포함한 데이터 무결성 관리.

2. 디버깅과 개선:
    - `UNIQUE constraint failed` 에러를 해결하기 위해 중복 데이터 검증 로직 추가.
    - 뷰 메서드에서 `NoneType` 반환 에러를 해결하기 위해 모든 분기에서 `Response` 객체를 반환하도록 수정.
    - Django ORM을 활용한 효율적인 데이터 필터링과 모델 간 관계 설정.


---
## 2. FEELINGS (나의 감정적인 반응, 느낌)

1. Django와 DRF의 생산성과 편의성에 감탄:    
    - 데이터베이스 작업과 RESTful API 설계가 직관적이고 간결하여 생산성을 극대화할 수 있음을 느꼈다.
    - 특히, DRF의 `Serializer`와 `APIView`를 활용하면 복잡한 로직도 구조적으로 관리할 수 있다는 점에서 큰 흥미를 느꼈다.

2. 디버깅 과정에서의 성취감:
    - 발생한 문제를 분석하고 해결하는 과정을 통해 코드의 안정성을 높이며 자신감을 얻었다.
    - 특히, 데이터 무결성을 보장하는 방법을 학습하며 더 나은 설계를 고민하게 되었다.


---
## 3. FINDINGS (그 상황으로부터 내가 배운 것)

1. Django ORM 및 DRF 활용:
    - Django ORM을 통해 데이터베이스와의 상호작용이 간소화되며, 기본 제공 기능으로 빠르게 프로토타입 개발이 가능하다는 점을 배움.
    - DRF의 `Serializer`와 `APIView`는 RESTful API 설계를 크게 단순화하며, 직관적인 코드 작성이 가능.

2. 에러 해결을 통한 경험 축적:
    - `UNIQUE constraint` 에러와 `NoneType` 반환 문제를 해결하며 디버깅 능력을 향상.
    - 데이터 유효성 검증과 예외 처리가 안정적인 애플리케이션 개발에 필수적임을 실감.

3. RESTful 설계와 보안의 중요성:
    - RESTful 설계의 구조적 장점과 DRF의 인증 및 권한 관리 기능을 활용하면 실제 애플리케이션의 보안성을 크게 높일 수 있다는 점을 배움.


---
## 4. FUTURE (배운 것을 미래에는 어떻게 적용할 지)
1. Django 및 DRF 프로젝트 확장:
    - Django와 DRF를 활용하여 CRUD와 인증이 포함된 API 중심의 백엔드 애플리케이션을 개발할 예정.
    - 실제 프로젝트에서 `APIView`와 `Serializer`를 활용하여 사용자 친화적이고 효율적인 기능을 설계.

2. 데이터 검증 및 디버깅 능력 강화:
    - 모델 설계 시 데이터 무결성을 보장하기 위해 유효성 검증 및 제약 조건을 더 철저히 적용할 계획.
    - 디버깅 경험을 토대로 에러 발생 가능성을 사전에 방지하고, 발생한 문제를 빠르게 해결할 수 있는 코드를 작성할 것.

3. 보안 강화:
    - DRF의 인증 및 권한 부여 시스템을 실무에 적용하여, 사용자와 데이터 보호를 우선시한 애플리케이션 개발을 목표로 함.
    - OAuth2, JWT 등 추가 인증 방식을 학습하고 적용해 볼 예정.

4. 다기능 애플리케이션 설계:
    - Django와 DRF를 활용하여 실제 사용자 니즈를 반영한 기능 중심 애플리케이션 개발에 도전.
    - 특히 API를 통해 프론트엔드와의 원활한 상호작용을 구현하여 통합 시스템 설계를 실습할 계획.