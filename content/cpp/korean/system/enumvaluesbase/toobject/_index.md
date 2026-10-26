---
title: ToObject()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 64비트 부호 없는 정수 값을 열거형 멤버로 변환합니다.
type: docs
weight: 40
url: /ko/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) 메서드

지정된 64비트 부호 없는 정수 값을 열거형 멤버로 변환합니다.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 반환할 열거형 유형. |
| value | **uint64_t** | 열거형 멤버로 변환할 값. |

### 반환값

값으로 설정된 열거형 인스턴스.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) 메서드

지정된 정수 값을 가진 객체를 열거형 멤버로 변환합니다.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | 반환할 열거형 유형. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 열거형 멤버로 변환할 값. |

### 반환값

값이 value인 열거형 객체.

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)