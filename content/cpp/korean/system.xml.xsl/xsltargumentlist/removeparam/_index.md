---
title: RemoveParam()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XsltArgumentList에서 매개변수를 제거합니다.
type: docs
weight: 66
url: /ko/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) 메서드

[XsltArgumentList](../)에서 매개변수를 제거합니다.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 제거할 매개변수의 이름입니다. [XsltArgumentList](../)는 전달된 이름이 유효한 로컬 이름인지 확인하지 않지만, 이름은 **nullptr**일 수 없습니다. |
| namespaceUri | const [String](../../../system/string/)\& | 제거할 매개변수의 네임스페이스 URI입니다. |

### 반환 값

매개변수 객체를 반환하며, 찾지 못한 경우 **nullptr**를 반환합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [String](../../../system/string/)
* 클래스 [XsltArgumentList](../)
* 네임스페이스 [System::Xml::Xsl](../../)
* 라이브러리 [Aspose.Slides](../../../)