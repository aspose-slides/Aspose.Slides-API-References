---
title: Deserialize()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 XML 文件反序列化為物件。
type: docs
weight: 14
url: /zh-hant/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) 方法


將 XML 文件反序列化為物件。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 用於讀取文件的串流。 |

### 返回值

[Object](../../../system/object/) 先前已序列化至給定的文件。

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) 方法


將 XML 文件反序列化為物件。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | 用於讀取文件的讀取器。 |

### 返回值

[Object](../../../system/object/) 先前已序列化至給定的文件。

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) 方法


將 XML 文件反序列化為物件。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 用於讀取文件的讀取器。 |

### 返回值

[Object](../../../system/object/) 先前已序列化至給定的文件。

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) 方法


將 XML 文件反序列化為物件。

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 用於讀取文件的讀取器。 |
| encodingStyle | [String](../../../system/string/) | 用於序列化物件的樣式。 |

### 返回值

[Object](../../../system/object/) 先前已序列化至給定的文件。

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [XmlSerializer](../)
* 類別 [TextReader](../../../system.io/textreader/)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml::Serialization](../../)
* 程式庫 [Aspose.Slides](../../../)