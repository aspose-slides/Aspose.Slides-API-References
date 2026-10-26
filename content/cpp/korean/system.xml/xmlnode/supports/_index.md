---
title: Supports()
second_title: Aspose.Slides for C++ API 레퍼런스
description: DOM 구현이 특정 기능을 구현하는지 테스트합니다.
type: docs
weight: 482
url: /ko/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) 메서드

DOM 구현이 특정 기능을 구현하는지 테스트합니다.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| feature | [String](../../../system/string/) | 테스트할 기능의 패키지 이름입니다. 이 이름은 대소문자를 구분하지 않습니다. |
| version | [String](../../../system/string/) | 테스트할 패키지 이름의 버전 번호입니다. 버전이 지정되지 않은 경우(null), 해당 기능의 모든 버전을 지원하면 메서드는 true를 반환합니다. |

### 반환 값

**true**가 지정된 버전에서 기능이 구현된 경우; 그렇지 않으면 **false**.

## 비고

다음 표는 **true**를 반환하는 조합을 설명합니다.

| 기능 | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNode](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)