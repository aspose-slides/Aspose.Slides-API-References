---
title: ToDecimal()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "지정된 문화별 서식 정보를 사용하여 이 인스턴스의 값을 동등한 System::Decimal 숫자로 변환합니다."
type: docs
weight: 170
url: /ko/system/iconvertible/todecimal/
---
## IConvertible::ToDecimal(System::SharedPtr\<System::IFormatProvider\>) method


이 인스턴스의 값을 지정된 문화별 서식 정보를 사용하여 동등한 [System::Decimal](../../decimal/) 숫자로 변환합니다.

```cpp
virtual System::Decimal System::IConvertible::ToDecimal(System::SharedPtr<System::IFormatProvider> provider)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | [System::IFormatProvider](../../iformatprovider/) 인터페이스 구현으로, 문화별 서식 정보를 제공합니다. |

### 반환 값

이 인스턴스의 값에 상응하는 [System::Decimal](../../decimal/) 숫자입니다.

## 관련 항목

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [Decimal](../../decimal/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [IConvertible](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)