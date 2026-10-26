---
title: SoapParameterStyle
second_title: Aspose.Slides for C++ API 레퍼런스
description: SOAP 메시지에서 매개변수 형식을 열거합니다.
type: docs
weight: 183
url: /ko/system.web.services.protocols/soapparameterstyle/
---
## SoapParameterStyle enum

SOAP 메시지에서 매개변수 형식을 열거합니다.

```cpp
enum class SoapParameterStyle
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Default | 0 | 클래스에 '[SoapDocumentServiceAttribute](../soapdocumentserviceattribute/)'가 적용되지 않은 경우 기본값은 'Wrapped'입니다. |
| Bare | 1 | 매개변수는 'Body' 요소 다음에 오는 XML 요소에 배치됩니다. |
| Wrapped | 2 | 매개변수는 'Body' 요소 다음에 오는 단일 XML 요소 안에 캡슐화됩니다. |

## 참조

* 네임스페이스 [System::Web::Services::Protocols](../)
* 라이브러리 [Aspose.Slides](../../)