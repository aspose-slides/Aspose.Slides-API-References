---
title: ToDateTime()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "지정된 문화별 형식 정보를 사용하여 이 인스턴스의 값을 동등한 System::DateTime 로 변환합니다."
type: docs
weight: 183
url: /ko/system/iconvertible/todatetime/
---
## IConvertible::ToDateTime(System::SharedPtr\<System::IFormatProvider\>) method

이 인스턴스의 값을 지정된 문화별 형식 정보를 사용하여 동등한 [System::DateTime](../../datetime/) 로 변환합니다.

```cpp
virtual System::DateTime System::IConvertible::ToDateTime(System::SharedPtr<System::IFormatProvider> provider)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | 문화별 형식 정보를 제공하는 [System::IFormatProvider](../../iformatprovider/) 인터페이스 구현입니다. |

### 반환 값

이 인스턴스의 값과 동등한 [System::DateTime](../../datetime/) 인스턴스입니다.

## 또 보기

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [DateTime](../../datetime/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [IConvertible](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)