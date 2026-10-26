---
title: ReadElementContentAsObject()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 요소를 읽고 내용을 Object 로 반환합니다.
type: docs
weight: 469
url: /ko/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() method

현재 요소를 읽고 내용을 [Object](../../../system/object/) 로 반환합니다.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### 반환 값

가장 적절한 유형의 박스된 객체입니다. [XmlReader::get_ValueType](../get_valuetype/) 값에 따라 적절한 유형이 결정됩니다. 내용이 리스트 유형으로 지정된 경우, 이 메서드는 적절한 유형의 박스된 객체 배열을 반환합니다.

## XmlReader::ReadElementContentAsObject(String, String) method

지정된 로컬 이름과 네임스페이스 URI가 현재 요소와 일치하는지 확인한 후, 현재 요소를 읽고 내용을 [Object](../../../system/object/) 로 반환합니다.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 요소의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 요소의 네임스페이스 URI입니다. |

### 반환 값

가장 적절한 유형의 박스된 객체입니다. [XmlReader::get_ValueType](../get_valuetype/) 값에 따라 적절한 유형이 결정됩니다. 내용이 리스트 유형으로 지정된 경우, 이 메서드는 적절한 유형의 박스된 객체 배열을 반환합니다.

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [XmlReader](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)