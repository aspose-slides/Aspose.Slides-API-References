---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "파생 클래스에서 재정의될 경우, 지정된 XmlReader::get_Name 값을 가진 속성의 값을 가져옵니다."
type: docs
weight: 599
url: /ko/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) 메서드

파생 클래스에서 재정의될 경우, 지정된 [XmlReader::get_Name](../get_name/) 값을 가진 속성의 값을 가져옵니다.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 정규화된 이름입니다. |

### 반환 값

지정된 속성의 값입니다. 속성을 찾을 수 없거나 값이 [String::Empty](../../../system/string/empty/)인 경우, **nullptr**를 반환합니다.

## XmlReader::GetAttribute(String, String) 메서드

파생 클래스에서 재정의될 경우, 지정된 [XmlReader::get_LocalName](../get_localname/) 및 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 값을 가진 속성의 값을 가져옵니다.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI입니다. |

### 반환 값

지정된 속성의 값입니다. 속성을 찾을 수 없거나 값이 [String::Empty](../../../system/string/empty/)인 경우, **nullptr**를 반환합니다. 이 메서드는 리더를 이동하지 않습니다.

## XmlReader::GetAttribute(int32_t) 메서드

파생 클래스에서 재정의될 경우, 지정된 인덱스를 가진 속성의 값을 가져옵니다.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | 속성의 인덱스입니다. 인덱스는 0부터 시작합니다. (첫 번째 속성의 인덱스는 0입니다.) |

### 반환 값

지정된 속성의 값입니다. 이 메서드는 리더를 이동하지 않습니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)