---
title: EnumValues
second_title: Aspose.Slides for C++ API 레퍼런스
description: enum 타입 E의 열거형 상수에 대한 메타 정보를 제공합니다.
type: docs
weight: 794
url: /ko/system/enumvalues/
---
## EnumValues 클래스

Provides meta information about enumeration constants of enum type **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| E | 열거형의 타입 |

## 메서드

| 메서드 | 설명 |
| --- | --- |
|   [EnumValues](./enumvalues/)() | 인스턴스를 생성합니다. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | 열거형 **E**의 모든 이름을 포함하는 배열을 반환합니다. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | 지정된 열거형에 있는 상수들의 이름 배열을 검색합니다. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | 지정된 열거형의 기본 타입을 반환합니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | 지정된 열거형의 기본 타입을 반환합니다. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | 지정된 이름을 가진 열거형 상수의 박싱된 값을 반환합니다. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | 지정된 값을 가진 열거형 상수의 박싱된 값을 반환합니다. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | 열거형 **E**의 모든 값을 포함하는 배열을 반환합니다. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | 지정된 열거형 타입의 모든 값을 포함하는 배열을 반환합니다. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 지정된 열거형 타입에서 지정된 이름을 가진 열거형 상수의 값을 나타내는 객체를 반환합니다. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | 지정된 64비트 부호 없는 정수 값을 열거형 멤버로 변환합니다. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 정수 값을 가진 지정된 객체를 열거형 멤버로 변환합니다. |
| virtual  [~EnumValues](./~enumvalues/)() | 소멸자. |

## 참고

* 클래스 [EnumValuesBase](../enumvaluesbase/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)