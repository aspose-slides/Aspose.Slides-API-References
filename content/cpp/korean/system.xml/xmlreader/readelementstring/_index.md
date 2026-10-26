---
title: ReadElementString()
second_title: Aspose.Slides C++ API 레퍼런스
description: "텍스트 전용 요소를 읽습니다. 그러나 이 작업을 보다 직접적으로 처리할 수 있기 때문에 XmlReader::ReadElementContentAsString 메서드를 사용하는 것이 권장됩니다."
type: docs
weight: 859
url: /ko/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() 메서드


텍스트 전용 요소를 읽습니다. 그러나 이 작업을 보다 직접적으로 처리할 수 있기 때문에 [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) 메서드를 사용하는 것이 권장됩니다.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```


### 반환 값

읽은 요소에 포함된 텍스트입니다. 요소가 비어 있으면 빈 문자열을 반환합니다.

## XmlReader::ReadElementString(String) 메서드


텍스트 전용 요소를 읽기 전에 찾아진 요소의 [XmlReader::get_Name](../get_name/) 값이 주어진 문자열과 일치하는지 확인합니다. 그러나 이 작업을 보다 직접적으로 처리할 수 있기 때문에 [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) 메서드를 사용하는 것이 권장됩니다.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 확인할 이름입니다. |

### 반환 값

읽은 요소에 포함된 텍스트입니다. 요소가 비어 있으면 빈 문자열을 반환합니다.

## XmlReader::ReadElementString(String, String) 메서드


텍스트 전용 요소를 읽기 전에 찾아진 요소의 [XmlReader::get_LocalName](../get_localname/)와 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 값이 주어진 문자열과 일치하는지 확인합니다. 그러나 이 작업을 보다 직접적으로 처리할 수 있기 때문에 [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) 메서드를 사용하는 것이 권장됩니다.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 확인할 로컬 이름입니다. |
| ns | [String](../../../system/string/) | 확인할 네임스페이스 URI입니다. |

### 반환 값

읽은 요소에 포함된 텍스트입니다. 요소가 비어 있으면 빈 문자열을 반환합니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)