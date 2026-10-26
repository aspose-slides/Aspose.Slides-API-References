---
title: ToString()
second_title: Aspose.Slides for C++ API 참조
description: "이 인스턴스의 값을 지정된 문화별 서식 정보를 사용하여 동등한 System::String 로 변환합니다."
type: docs
weight: 196
url: /ko/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) 메서드

이 인스턴스의 값을 지정된 문화별 서식 정보를 사용하여 동등한 [System::String](../../string/) 로 변환합니다.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) 인터페이스 구현으로, 문화별 서식 정보를 제공합니다. |

### 반환 값

[System::String](../../string/) 인스턴스는 이 인스턴스의 값과 동등합니다.

## IConvertible::ToString() const 메서드

C# [Object.ToString()](../../object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다.

```cpp
virtual String System::Object::ToString() const
```

### 반환 값

최종 클래스에서 제공하는 [String](../../string/) 표현.

## 참조

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [IConvertible](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)