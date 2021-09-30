# iOS 스터디
with 대장 택현, 민수1 영광, 에그머니 완숙, 민수2 신희


## 시간

* 알고리즘 - 매주 화목 8시 - 9시 30분
* iOS - 매주 일요일 오후 8시 - 10시


## 정책

* 벌금 5000원!!


## 1주차

### 1st

- (optional) HIG
- 앱설계 (디자인) 원칙
- 기획 / 디자인 세부 과정
- 멀티 터치
- 뷰 만들기 (좌표, 높이, 넓이, 레이아웃, 비율, 색상, 글꼴)
- ADS
- Segue의 정체

### 2nd

- GIT
- viewController 역할과 콜백
- viewControllers (root, system, container, custom, navigation, split)
- Scene, UIScene, UIWindowScene
- 뷰의 상태 변화
- Modal과 Transition
- 코코아 터치
- IBOutlet vs IBAction
- MVC와 프로그램의 구조
- OpenURL - 앱간 이동

### 3rd

- Static Typing, Duck-type System, Dynamic System
- Type Inference
- Safety (type safety, no pointers, optionals, boundary check)
- 이벤트와 반응 표시
- 앱의 핵심 객체들 (UIApplication, AppDelegate, SceneDelegate, ViewController, UIWindow)
- @main
- 값 검증 -> 런타임 검증 vs 컴파일 타임 검증
- namespace, nested, typealias
- protocol과 value oriented 프로그래밍
- 능동적 객체 vs 수동적 객체
- 강한 참조 vs 약한 참조
- 단위 테스트
- 클래스 다이어그램, UML, state/flow diagram
- 확장 문법(subscript, protocol, extension generic)
- CustomStringConvertible, toString()

## 2주차

### 1st
- struct vs class
- Recycle Problem(ARC)
- 접근제어 (open, public, internal, fileprivate, private)
- 클래스 상속 vs 프로토콜 사용
- swift 메모리 모델

### 2nd
- Waterfuall Process
- 소프트웨어 개발 V 패턴
- 유닛 테스트
    - A-Trip
    - Right - BICEP
    - 경계 조건과 CORRECT

### 3rd
- 다형성
- Designated initializer, Convernience Initializer
- 2단계 초기화
  - 추가하기 완식
- Delegate 구조
- 타입 변환, loose Coupling 지향

## 3주차

### 1st
- iOS 좌표시스템 
- Frame VS Bounds
- 수동레이아웃
- 오토레이아웃
- 오토레이아웃(stackview)
- UITraitCollection
- XIB - filesOwner?
- Archived View Object
- Property Wrapper
- 스토리보드의 이해

### 2nd
- OOP 추상화
- encapsulation
- polymorphism
- 객체설계원칙-SOLID
  - 210903 
- cohesion , Coupling
- dependency

### 3rd
- 앱 아키텍처
- App. Life-cycle
- Scene-based Life cycle
- copy와 mutableCopy
- NSCopying
- Keyed Archiving
- NSCoding
- Archiving & Unarchiving

## 4주차

### 1st

* UIKit 계층 구조 파악
* UIResponder란? 동작방식
* 사용자의 터치(이벤트)로부터 뷰로 보여지기 까지의 과정
* Gesture Recognizer의 정체
* 런루프의 정체
    - 210926 완숙 [RunLoop란?](https://wansook0316.github.io/dv/ios/2021/09/19/iOS-Exprience-14-iOS-RunLoop.html)
* UIApplication의 정체
    - 210926 완숙 [UIApplication이란?](https://wansook0316.github.io/dv/ios/2021/09/19/iOS-Exprience-15-iOS-UIApplication.html)
* Hittest (공식문서 내용이 들어가야 할듯?)
* UIEvent의 종류
    - 210926 택현 [iOS에서 Event를 처리하는 방법](https://wandering-office-654.notion.site/iOS-Event-29db093108ce4c49bbdf17f6d14a7e6b)
* Responder Chain - isUserInteractionEnabled
    - 210926 택현 [iOS에서 Event를 처리하는 방법](https://wandering-office-654.notion.site/iOS-Event-29db093108ce4c49bbdf17f6d14a7e6b)


### 2nd
* MVC, MVVM
    - 210926 신희
* KeyValue-Observer (KVO)
* NotificationCenter 동작 흐름
* Combine이란?, Reactive programming??
* Property Wrapper
* UserDefaults의 활용처, 동작방식
* Presenter, Usecase?
    - 210926 신희

### 3rd

- 뷰와 비즈니스 로직의 분리
- Archieve (View, Data)
- Core Graphics, UIKit
- 앱 라이프사이클(Scene-based)과 UserDefaults
- Bundles
- UITableView 
    -> Plain, Grouped, Static, Dynamic
    -> ReusableQueue
    -> BatchUpdate
    -> 데이터 소스와 델리게이트 관계
    - 210926 영광
- Adapter

## 5주차

### 1st


### 2nd

- CollectionView
  - 211003 택현

### 3rd




# 필수 공부

* 데이터 베이스 기초 용어
* LRU 캐시 재구현
* LinkedList 구현
* 트리 구현
* 이진 탐색 트리 구현
* HTTP 공부
* 딕셔너리(hashMap) 구현
* OS 스케쥴링

# 추가공부

* LocalizedString
* WWDC Memory Deep Dive - 한국어가 있음
* .map의 정체
* [연관값 없이 enum 비교하기 - 패턴매칭](https://forums.swift.org/t/comparing-enums-without-their-associated-values/18944)
* [enum RawPresentable, 메모리 구조](https://jcsoohwancho.github.io/2019-08-19-enum-%EB%8D%94-%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0-CaseIterable,-RawPresentable,-%EB%A9%94%EB%AA%A8%EB%A6%AC%EA%B5%AC%EC%A1%B0/)
* [프로퍼티 감시자는 init에서 호출되지 않는다.](https://docs.swift.org/swift-book/LanguageGuide/Properties.html#//apple_ref/doc/uid/TP40014097-CH14-XID_368)
* [RxSwift의 개념과 MVVM 예시](https://wansook0316.github.io/dv/ios/2021/09/22/iOS-RxSwift-01-Concept.html)
* UseCase Pattern
* Repository Pattern
