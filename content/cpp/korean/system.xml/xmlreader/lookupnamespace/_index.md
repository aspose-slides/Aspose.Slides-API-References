---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 참조
description: 파생 클래스에서 오버라이드될 경우 현재 요소의 범위에서 네임스페이스 접두사를 해결합니다.
type: docs
weight: 729
url: /ko/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) 메서드


When overridden in a derived class, resolves a namespace prefix in the current element's scope.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 해결하려는 네임스페이스 URI에 해당하는 접두사입니다. 기본 네임스페이스와 일치시키려면 빈 문자열을 전달하십시오. |

### 반환값

The namespace URI to which the prefix maps or **nullptr** if no matching prefix is found.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)