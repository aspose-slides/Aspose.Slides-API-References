---
title: ToChar()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문화별 형식 정보를 사용하여 이 인스턴스의 값을 동등한 유니코드 문자로 변환합니다.
type: docs
weight: 27
url: /ko/system/iconvertible/tochar/
---
## IConvertible::ToChar(System::SharedPtr\<System::IFormatProvider\>) 메서드

이 인스턴스의 값을 지정된 문화별 형식 정보를 사용하여 동일한 유니코드 문자로 변환합니다.

```cpp
virtual char_t System::IConvertible::ToChar(System::SharedPtr<System::IFormatProvider> provider)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 문화별 형식 정보를 제공하는 [System::IFormatProvider](../../iformatprovider/) 인터페이스 구현입니다. |

### 반환값

이 인스턴스의 값에 해당하는 유니코드 문자입니다.

## 관련 항목

* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [IConvertible](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)