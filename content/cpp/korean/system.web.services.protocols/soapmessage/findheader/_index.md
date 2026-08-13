---
title: FindHeader()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 헤더 유형으로 헤더 매핑을 찾습니다.
type: docs
weight: 352
url: /ko/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) 메서드

지정된 헤더 유형으로 헤더 매핑을 찾습니다.

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | 헤더 매핑의 컬렉션. |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | 검색할 헤더 유형. |

### 반환 값

헤더 매핑.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [SoapMessage](../)
* 네임스페이스 [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)