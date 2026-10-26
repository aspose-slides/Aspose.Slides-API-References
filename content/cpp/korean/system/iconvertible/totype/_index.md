---
title: ToType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "이 인스턴스의 값을 지정된 System::Type과 동등한 값으로, 지정된 문화별 형식 정보를 사용하여 System::Object 로 변환합니다."
type: docs
weight: 209
url: /ko/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) method

이 인스턴스의 값을 지정된 System::Type의 동등한 값으로, 지정된 문화별 형식 정보를 사용하여 [System::Object](../../object/) 로 변환합니다.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | 이 인스턴스의 값이 변환되는 System::Type. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 문화별 형식 정보를 제공하는 [System::IFormatProvider](../../iformatprovider/) 인터페이스 구현. |

### 반환값

conversionType 형식의 [System::Object](../../object/) 인스턴스로, 이 인스턴스의 값과 동등한 값을 가집니다.

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)