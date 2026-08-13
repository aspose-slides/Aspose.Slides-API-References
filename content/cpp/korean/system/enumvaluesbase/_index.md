---
title: EnumValuesBase
second_title: Aspose.Slides for C++ API 레퍼런스
description: 열거형 타입의 메타 정보를 나타내는 클래스를 위한 기본 클래스입니다.
type: docs
weight: 807
url: /ko/system/enumvaluesbase/
---
## EnumValuesBase 클래스

열거형 유형의 메타 정보를 나타내는 클래스를 위한 기본 클래스입니다.

```cpp
class EnumValuesBase
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | 지정된 열거형에 있는 상수들의 이름 배열을 반환합니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | 지정된 열거형의 기본 유형을 반환합니다. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | 지정된 열거형 유형의 모든 값을 포함하는 배열을 반환합니다. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 지정된 이름을 가진, 지정된 열거형 유형의 열거형 상수 값을 나타내는 객체를 반환합니다. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | 지정된 64비트 부호 없는 정수 값을 열거형 멤버로 변환합니다. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 정수 값을 가진 지정된 객체를 열거형 멤버로 변환합니다. |
## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)