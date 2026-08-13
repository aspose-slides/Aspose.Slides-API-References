---
title: IsClientFaultCode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 코드가 'Client' SOAP 오류 코드와 같은지 확인합니다.
type: docs
weight: 105
url: /ko/system.web.services.protocols/details_soapexception/isclientfaultcode/
---
## Details_SoapException::IsClientFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) 메서드

지정된 코드가 'Client' SOAP 오류 코드와 동일한지 확인합니다.

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsClientFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 확인할 SOAP 오류 코드입니다. |

## 반환값

지정된 코드가 'Client' SOAP 오류 코드와 동일하면 true, 그렇지 않으면 false.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* 클래스 [Details_SoapException](../)
* 네임스페이스 [System::Web::Services::Protocols](../../)
* 라이브러리 [Aspose.Slides](../../../)