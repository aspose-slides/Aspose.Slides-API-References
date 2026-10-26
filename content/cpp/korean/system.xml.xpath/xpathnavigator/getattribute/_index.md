---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 로컬 이름 및 네임스페이스 URI를 가진 속성의 값을 반환합니다.
type: docs
weight: 482
url: /ko/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) 메서드


지정된 로컬 이름 및 네임스페이스 URI를 가진 속성의 값을 반환합니다.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 속성의 로컬 이름입니다. **localName**은 대소문자를 구분합니다. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI입니다. |

### 반환값

지정된 속성의 값을 포함하는 [String](../../../system/string/); 일치하는 속성을 찾지 못했거나 [XPathNavigator](../)이(가) 요소 노드에 위치하지 않은 경우 [String::Empty](../../../system/string/empty/).

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)