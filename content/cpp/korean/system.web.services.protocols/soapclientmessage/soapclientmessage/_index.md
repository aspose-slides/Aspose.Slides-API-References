---
title: SoapClientMessage()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 66
url: /ko/system.web.services.protocols/soapclientmessage/soapclientmessage/
---
## SoapClientMessage::SoapClientMessage(System::SharedPtr\<SoapHttpClientProtocol\>, System::SharedPtr\<SoapMethodStubInfo\>, String, System::ArrayPtr\<System::SharedPtr\<Object\>\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Web::Services::Protocols::SoapClientMessage::SoapClientMessage(System::SharedPtr<SoapHttpClientProtocol> client, System::SharedPtr<SoapMethodStubInfo> msi, String url, System::ArrayPtr<System::SharedPtr<Object>> parameters)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| client | [System::SharedPtr](../../../system/sharedptr/)\<[SoapHttpClientProtocol](../../soaphttpclientprotocol/)\> | 클라이언트 프록시 클래스의 인스턴스입니다. |
| msi | [System::SharedPtr](../../../system/sharedptr/)\<SoapMethodStubInfo\> | 메서드 스텁 정보. |
| url | [String](../../../system/string/) | XML 웹 서비스의 URL. |
| parameters | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 매개변수 컬렉션. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SoapHttpClientProtocol](../../soaphttpclientprotocol/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [SoapClientMessage](../)
* Namespace [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)