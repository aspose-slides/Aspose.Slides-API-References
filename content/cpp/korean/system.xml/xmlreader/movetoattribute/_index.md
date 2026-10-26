---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "파생 클래스에서 재정의될 경우, 지정된 XmlReader::get_Name 값의 속성으로 이동합니다."
type: docs
weight: 625
url: /ko/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) 메서드

파생 클래스에서 재정의될 경우, 지정된 [XmlReader::get_Name](../get_name/) 값의 속성으로 이동합니다.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 정규화된 이름. |

### 반환값

**true**이면 속성이 발견된 것이며, 그렇지 않으면 **false**입니다. **false**인 경우, 리더의 위치는 변경되지 않습니다.

## XmlReader::MoveToAttribute(String, String) 메서드

파생 클래스에서 재정의될 경우, 지정된 [XmlReader::get_LocalName](../get_localname/) 및 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 값의 속성으로 이동합니다.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 로컬 이름. |
| ns | [String](../../../system/string/) | 속성의 네임스페이스 URI. |

### 반환값

**true**이면 속성이 발견된 것이며, 그렇지 않으면 **false**입니다. **false**인 경우, 리더의 위치는 변경되지 않습니다.

## XmlReader::MoveToAttribute(int32_t) 메서드

파생 클래스에서 재정의될 경우, 지정된 인덱스의 속성으로 이동합니다.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | 속성의 인덱스. |

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)