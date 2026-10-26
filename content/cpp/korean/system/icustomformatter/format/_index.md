---
title: Format()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 형식을 사용하여 현재 객체가 나타내는 값의 문자열 표현을 반환합니다.
type: docs
weight: 1
url: /ko/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) 메서드

지정된 형식을 사용하여 현재 객체가 나타내는 값의 문자열 표현을 반환합니다.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| format | [System::String](../../string/) | 문자열 형식 |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | 포맷할 객체 |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 형식 정보를 제공하는 객체 |

### 반환 값

**arg**는 **format** 및 **formatProvider**에 의해 지정된 형식에 따라 포맷된 문자열 표현입니다.

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [Object](../../object/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [ICustomFormatter](../)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)