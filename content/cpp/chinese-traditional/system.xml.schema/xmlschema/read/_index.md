---
title: Read()
second_title: Aspose.Slides for C++ API 參考
description: "從提供的 IO::TextReader 讀取 XML Schema。"
type: docs
weight: 365
url: /zh-hant/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) 方法

從提供的 [IO::TextReader](../../../system.io/textreader/) 讀取 XML [Schema](../../)。

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | 包含要讀取的 XML [Schema](../../) 的 [IO::TextReader](../../../system.io/textreader/)。 |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有關 XML [Schema](../../) 語法錯誤資訊的驗證事件處理程序。 |

### 返回值

代表 XML [Schema](../../) 的 [XmlSchema](../) 物件。

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) 方法

從提供的資料流讀取 XML [Schema](../../)。

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 提供的資料串流。 |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有關 XML [Schema](../../) 語法錯誤資訊的驗證事件處理程序。 |

### 返回值

代表 XML [Schema](../../) 的 [XmlSchema](../) 物件。

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) 方法

從提供的 [XmlReader](../../../system.xml/xmlreader/) 讀取 XML [Schema](../../)。

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | 包含要讀取的 XML [Schema](../../) 的 [XmlReader](../../../system.xml/xmlreader/)。 |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | 接收有關 XML [Schema](../../) 語法錯誤資訊的驗證事件處理程序。 |

### 返回值

代表 XML [Schema](../../) 的 [XmlSchema](../) 物件。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* 類別 [XmlSchema](../)
* 類別 [TextReader](../../../system.io/textreader/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 命名空間 [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)