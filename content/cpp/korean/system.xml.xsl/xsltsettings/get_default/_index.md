---
title: get_Default()
second_title: Aspose.Slides for C++ API 참조
description: 기본 설정이 적용된 XsltSettings 객체를 반환합니다. XSLT document() 함수와 삽입된 스크립트 블록에 대한 지원은 비활성화됩니다.
type: docs
weight: 1
url: /ko/system.xml.xsl/xsltsettings/get_default/
---
## XsltSettings::get_Default() 메서드


기본 설정이 적용된 [XsltSettings](../) 객체를 반환합니다. XSLT **document()** 함수와 삽입된 스크립트 블록에 대한 지원은 비활성화됩니다.

```cpp
static SharedPtr<XsltSettings> System::Xml::Xsl::XsltSettings::get_Default()
```


### 반환 값

[XsltSettings](../) 객체이며, [XsltSettings::set_EnableDocumentFunction](../set_enabledocumentfunction/) 및 [XsltSettings::set_EnableScript](../set_enablescript/) 옵션이 **false**로 설정됩니다.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XsltSettings](../)
* 네임스페이스 [System::Xml::Xsl](../../)
* 라이브러리 [Aspose.Slides](../../../)