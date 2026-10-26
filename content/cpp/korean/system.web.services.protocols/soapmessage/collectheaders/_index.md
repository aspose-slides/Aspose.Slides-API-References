---
title: CollectHeaders()
second_title: Aspose.Slides for C++ API 레퍼런스
description: SOAP 헤더의 내부 컬렉션을 설정합니다.
type: docs
weight: 326
url: /ko/system.web.services.protocols/soapmessage/collectheaders/
---
## SoapMessage::CollectHeaders(System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, SoapHeaderDirection) 메서드


SOAP 헤더의 내부 컬렉션을 설정합니다.

```cpp
void System::Web::Services::Protocols::SoapMessage::CollectHeaders(System::SharedPtr<Object> target, System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headers, SoapHeaderDirection direction)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| target | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | SOAP 헤더를 가져올 객체입니다. |
| headers | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | 내부 컬렉션을 채우는 헤더 컬렉션입니다. |
| direction | [SoapHeaderDirection](../../soapheaderdirection/) | SOAP 헤더 방향입니다. |

## 관련 보기

* Enum [SoapHeaderDirection](../../soapheaderdirection/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [SoapMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)