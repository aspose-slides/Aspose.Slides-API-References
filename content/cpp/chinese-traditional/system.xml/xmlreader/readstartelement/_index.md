---
title: ReadStartElement()
second_title: Aspose.Slides for C++ API 參考
description: 檢查當前節點是否為元素，並將閱讀器前移至下一個節點。
type: docs
weight: 846
url: /zh-hant/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() 方法

檢查當前節點是否為元素，並將閱讀器前移至下一個節點。

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) 方法

檢查當前內容節點是否為具有給定 [XmlReader::get_Name](../get_name/) 值的元素，並將閱讀器前移至下一個節點。

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 元素的限定名稱。 |

## XmlReader::ReadStartElement(String, String) 方法

檢查當前內容節點是否為具有給定 [XmlReader::get_LocalName](../get_localname/) 和 [XmlReader::get_NamespaceURI](../get_namespaceuri/) 值的元素，並將閱讀器前移至下一個節點。

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 元素的本地名稱。 |
| ns | [String](../../../system/string/) | 元素的命名空間 URI。 |

## 另請參閱

* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)