---
title: RemoveExtensionObject()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XsltArgumentList에서 네임스페이스 URI와 연결된 객체를 제거합니다.
type: docs
weight: 79
url: /ko/system.xml.xsl/xsltargumentlist/removeextensionobject/
---
## XsltArgumentList::RemoveExtensionObject(const String\&) 메서드


[XsltArgumentList](../)에서 네임스페이스 URI와 연결된 객체를 제거합니다.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveExtensionObject(const String &namespaceUri)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| namespaceUri | const [String](../../../system/string/)\& | 제거할 객체와 연결된 네임스페이스 URI. |

### 반환 값

네임스페이스 URI와 일치하는 객체를 반환하며, 찾지 못한 경우 **nullptr**를 반환합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [String](../../../system/string/)
* 클래스 [XsltArgumentList](../)
* 네임스페이스 [System::Xml::Xsl](../../)
* 라이브러리 [Aspose.Slides](../../../)