---
title: Enum
second_title: Aspose.Slides for C++ API 참조
description: 열거형 타입의 값에 대해 일부 작업을 수행하는 메서드를 제공합니다. 이는 인스턴스 서비스를 갖지 않는 정적 타입입니다. 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 1587
url: /ko/system/enum/
---
## 열거형 구조체

열거형 값에 대해 일부 작업을 수행하는 메서드를 제공합니다. 이는 인스턴스 서비스가 없는 정적 타입입니다. 어떤 방법으로든 인스턴스를 생성해서는 안 됩니다.

```cpp
template<class E,class Guard>class Enum
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| E | 클래스가 처리하는 값들의 열거형 타입 |
| Guard | **E**가 열거형 타입인지 확인하기 위한 서비스 타입 매개변수 |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static int [Compare](./compare/)(E, T) | 지정된 열거형 상수들의 값에 대한 산술 비교를 수행합니다. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | 지정된 값을 가진 열거형 상수의 이름을 반환합니다. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | 지정된 값을 가진 열거형 상수의 이름을 반환합니다. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | 열거형 **E**의 모든 멤버 이름을 포함하는 배열을 반환합니다. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | 열거형의 기본 타입을 반환합니다. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | 열거형 **E**의 모든 멤버를 포함하는 배열을 반환합니다. |
| static **bool** [HasFlag](./hasflag/)(E, E) | 지정된 열거형 값의 비트 표현에서 지정된 비트가 설정되어 있는지 확인합니다. |
| static **bool** [IsDefined](./isdefined/)(E) | 지정된 값이 열거형 타입 **E**의 멤버인지 여부를 판단합니다. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | 지정된 값이 열거형 타입 **T**의 멤버인지 여부를 판단합니다. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | 지정된 이름을 가진 값이 열거형 **E**의 멤버 중에 있는지 확인합니다. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | 지정된 문자열을 동등한 열거형 상수로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | 지정된 문자열을 동등한 열거형 상수로 변환을 시도합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | 지정된 문자열을 동등한 열거형 상수로 변환을 시도합니다. |

## 타입 별칭

| 타입 별칭 | 설명 |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | 열거형의 기본 타입에 대한 별칭입니다. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)