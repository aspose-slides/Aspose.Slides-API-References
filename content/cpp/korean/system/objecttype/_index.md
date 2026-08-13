---
title: ObjectType
second_title: Aspose.Slides for C++ API 레퍼런스
description: 객체 유형 getter를 구현하는 정적 메서드를 제공합니다. 이는 인스턴스 서비스를 갖지 않는 정적 유형이며, 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 1158
url: /ko/system/objecttype/
---
## ObjectType 클래스

객체 유형 getter를 구현하는 정적 메서드를 제공합니다. 이는 인스턴스 서비스를 갖지 않는 정적 유형이며, 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class ObjectType
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() 변환을 구현합니다. 스마트 포인터에 대한 오버로드. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() 변환을 구현합니다. 구조체에 대한 오버로드. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() 변환을 구현합니다. 예외에 대한 오버로드. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | typeof() 변환을 구현합니다. 원시 타입에 대한 오버로드. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | typeof() 변환을 구현합니다. [Nullable](../nullable/) 타입에 대한 오버로드. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() 변환을 구현합니다. 원시 타입에 대한 오버로드. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() 변환을 구현합니다. enum 타입에 대한 오버로드. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() 변환을 구현합니다. 구조체 및 포인터에 대한 오버로드. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() 변환을 구현합니다. [Nullable](../nullable/)에 대한 오버로드. |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() 변환을 구현합니다. MutlicastDelegate에 대한 오버로드. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() 변환을 구현합니다. 구조체 및 포인터에 대한 오버로드. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | typeof() 변환을 구현합니다. string 타입에 대한 오버로드. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드. |

## 참고

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)