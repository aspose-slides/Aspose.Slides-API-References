---
title: IsVersionMismatchFaultCode()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 코드가 'VersionMismatch' SOAP 오류 코드와 같은지 확인합니다.
type: docs
weight: 144
url: /ko/system.web.services.protocols/details_soapexception/isversionmismatchfaultcode/
---
## Details_SoapException::IsVersionMismatchFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) 메서드

지정된 코드가 'VersionMismatch' SOAP Fault 코드와 같은지 확인합니다.

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsVersionMismatchFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | 확인할 SOAP Fault 코드. |

### 반환 값

지정된 코드가 'VersionMismatch' SOAP Fault 코드와 같을 경우 true, 그렇지 않으면 false.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* 클래스 [Details_SoapException](../)
* 네임스페이스 [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)