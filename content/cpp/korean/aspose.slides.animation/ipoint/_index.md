---
title: IPoint
second_title: Aspose.Slides for C++ API 레퍼런스
description: 애니메이션 포인트를 나타냅니다.
type: docs
weight: 313
url: /ko/aspose.slides.animation/ipoint/
---
## IPoint 클래스

애니메이션 포인트를 나타냅니다.

```cpp
class IPoint : public virtual System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 구문을 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN이 동일하게 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN이 동일하게 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual [System::String](../../system/string/) [get_Formula](./get_formula/)() | 값, from, to, by 속성 내의 수식은 다음과 같이 구성될 수 있습니다: 표준 산술 연산자: \\uFFFD+\\uFFFD, \\uFFFD-\\uFFFD, \\uFFFD*\\uFFFD, \\uFFFD/\\uFFFD, \\uFFFD^\\uFFFD, \\uFFFD\\uFFFD (mod) 상수: \\uFFFDpi\\uFFFD \\uFFFDe\\uFFFD 조건 연산자: \\uFFFDabs\\uFFFD, \\uFFFDmin\\uFFFD, \\uFFFDmax\\uFFFD, \\uFFFD?\\uFFFD (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: \\uFFFDsin()\\uFFFD, \\uFFFDcos()\\uFFFD, \\uFFFDtan()\\uFFFD, \\uFFFDasin()\\uFFFD, \\uFFFDacos()\\uFFFD, \\uFFFDatan()\\uFFFD 자연 로그 \\uFFFDln()\\uFFFD 속성 참조 (호스트 지원 속성) |
| virtual **float** [get_Time](./get_time/)() | 시간 값을 나타냅니다. **float**를 읽습니다. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | 포인트 값을 나타냅니다. 허용 타입: bool, [ColorFormat](../../aspose.slides/colorformat/), float, int, string. [System::Object](../../system/object/)를 읽습니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 타입의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현하여 잠급니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 구성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 참조로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 참조로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 문자열 및 nullptr 경우에 대한 [Object::ReferenceEquals](../../system/object/referenceequals/) 특수화. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [set_Formula](./set_formula/)([System::String](../../system/string/)) | 값, from, to, by 속성 내의 수식은 다음과 같이 구성될 수 있습니다: 표준 산술 연산자: \\uFFFD+\\uFFFD, \\uFFFD-\\uFFFD, \\uFFFD*\\uFFFD, \\uFFFD/\\uFFFD, \\uFFFD^\\uFFFD, \\uFFFD\\uFFFD (mod) 상수: \\uFFFDpi\\uFFFD \\uFFFDe\\uFFFD 조건 연산자: \\uFFFDabs\\uFFFD, \\uFFFDmin\\uFFFD, \\uFFFDmax\\uFFFD, \\uFFFD?\\uFFFD (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: \\uFFFDsin()\\uFFFD, \\uFFFDcos()\\uFFFD, \\uFFFDtan()\\uFFFD, \\uFFFDasin()\\uFFFD, \\uFFFDacos()\\uFFFD, \\uFFFDatan()\\uFFFD 자연 로그 \\uFFFDln()\\uFFFD 속성 참조 (호스트 지원 속성) |
| virtual void [set_Time](./set_time/)(**float**) | 시간 값을 나타냅니다. **float**를 씁니다. |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 포인트 값을 나타냅니다. 허용 타입: bool, [ColorFormat](../../aspose.slides/colorformat/), float, int, string. [System::Object](../../system/object/)를 씁니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문을 구현하여 잠금을 해제합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |
## 참조

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides::Animation](../)
* 라이브러리 [Aspose.Slides](../../)