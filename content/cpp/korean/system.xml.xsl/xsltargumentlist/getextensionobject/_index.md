---
title: GetExtensionObject()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 주어진 네임스페이스와 연결된 객체를 반환합니다.
type: docs
weight: 27
url: /ko/system.xml.xsl/xsltargumentlist/getextensionobject/
---
## XsltArgumentList::GetExtensionObject(const String\&) method


주어진 네임스페이스와 연결된 객체를 반환합니다.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetExtensionObject(const String &namespaceUri)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| namespaceUri | const [String](../../../system/string/)\& | 객체의 네임스페이스 URI. |

### 반환값

네임스페이스 URI 객체이며, 찾을 수 없으면 **nullptr**을 반환합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [String](../../../system/string/)
* 클래스 [XsltArgumentList](../)
* 네임스페이스 [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)