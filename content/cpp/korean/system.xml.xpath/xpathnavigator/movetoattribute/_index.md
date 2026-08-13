---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 참조
description: XPathNavigator를 일치하는 로컬 이름 및 네임스페이스 URI를 가진 속성으로 이동합니다.
type: docs
weight: 495
url: /ko/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute(String, String) 메서드


[XPathNavigator](../)를 일치하는 로컬 이름 및 네임스페이스 URI를 가진 속성으로 이동합니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 속성의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI입니다; 빈 네임스페이스인 경우 **nullptr**. |

### 반환값

**true**가 [XPathNavigator](../)가 속성으로 성공적으로 이동했을 때; 그렇지 않으면 **false**. **false**인 경우, [XPathNavigator](../)의 위치는 변경되지 않습니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)