---
title: idx_get()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 지정된 인덱스의 속성 값을 가져옵니다.
type: docs
weight: 612
url: /ko/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) 메서드


파생 클래스에서 재정의될 경우, 지정된 인덱스의 속성 값을 가져옵니다.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | 속성의 인덱스. |

### 반환값

지정된 속성의 값.

## XmlReader::idx_get(String) 메서드


파생 클래스에서 재정의될 경우, 지정된 [XmlReader::get_Name](../get_name/) 값의 속성 값을 가져옵니다.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 정규화된 이름. |

### 반환값

지정된 속성의 값. 속성을 찾을 수 없으면 **nullptr** 가 반환됩니다.

## XmlReader::idx_get(String, String) 메서드


파생 클래스에서 재정의될 경우, 지정된 [XmlReader::get_LocalName](../get_localname/) 및 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 값의 속성 값을 가져옵니다.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 속성의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 속성의 네임스페이스 URI. |

### 반환값

지정된 속성의 값. 속성을 찾을 수 없으면 **nullptr** 가 반환됩니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)