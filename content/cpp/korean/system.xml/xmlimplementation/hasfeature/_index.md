---
title: HasFeature()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Document Object Model (DOM) 구현이 특정 기능을 구현하는지 테스트합니다.
type: docs
weight: 14
url: /ko/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) 메서드

Document [Object](../../../system/object/) Model (DOM) 구현이 특정 기능을 구현하는지 테스트합니다.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | 테스트할 기능의 패키지 이름입니다. 이 이름은 대소문자를 구분하지 않습니다. |
| strVersion | const [String](../../../system/string/)\& | 테스트할 패키지 이름의 버전 번호입니다. 버전이 지정되지 않은 경우(**nullptr**), 해당 기능의 모든 버전을 지원하면 메서드는 **true**를 반환합니다. |

### 반환 값
**true**가 지정된 버전에 기능이 구현된 경우; 그렇지 않으면 **false**.
## 비고



다음 표는 **HasFeature**가 **true**를 반환하게 하는 조합을 보여줍니다. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlImplementation](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)