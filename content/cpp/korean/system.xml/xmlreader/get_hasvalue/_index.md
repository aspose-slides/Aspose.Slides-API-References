---
title: get_HasValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "파생 클래스에서 재정의될 경우, 현재 노드가 XmlReader::get_Value 값을 가질 수 있는지 여부를 나타내는 값을 가져옵니다."
type: docs
weight: 79
url: /ko/system.xml/xmlreader/get_hasvalue/
---
## XmlReader::get_HasValue() method


파생 클래스에서 재정의될 경우, 현재 노드가 [XmlReader::get_Value](../get_value/) 값을 가질 수 있는지 여부를 나타내는 값을 가져옵니다.

```cpp
virtual bool System::Xml::XmlReader::get_HasValue()
```


### 반환값

**true**는 현재 리더가 위치한 노드가 **Value**를 가질 수 있는 경우이며, 그렇지 않으면 **false**입니다. **false**인 경우, 노드는 [String::Empty](../../../system/string/empty/) 값을 가집니다.

## 참고

* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)