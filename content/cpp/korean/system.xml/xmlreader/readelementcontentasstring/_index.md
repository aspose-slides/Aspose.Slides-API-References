---
title: ReadElementContentAsString()
second_title: Aspose.Slides for C++ API 참조
description: 현재 요소를 읽고 내용을 String 객체로 반환합니다.
type: docs
weight: 573
url: /ko/system.xml/xmlreader/readelementcontentasstring/
---
## XmlReader::ReadElementContentAsString() 메서드


현재 요소를 읽고 내용을 [String](../../../system/string/) 객체로 반환합니다.

```cpp
virtual String System::Xml::XmlReader::ReadElementContentAsString()
```


### 반환 값

요소 내용이 [String](../../../system/string/) 객체로 반환됩니다.

## XmlReader::ReadElementContentAsString(String, String) 메서드


지정된 로컬 이름 및 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 [String](../../../system/string/) 객체로 반환합니다.

```cpp
virtual String System::Xml::XmlReader::ReadElementContentAsString(String localName, String namespaceURI)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 요소의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 요소의 네임스페이스 URI입니다. |

### 반환 값

요소 내용이 [String](../../../system/string/) 객체로 반환됩니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)