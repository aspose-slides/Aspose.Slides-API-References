---
title: Load()
second_title: Aspose.Slides for C++ API 參考文檔
description: 從指定的 URL 載入 XML 文件。
type: docs
weight: 508
url: /zh-hant/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) 方法

從指定的 URL 載入 XML 文件。

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | [String](../../../system/string/) | 載入之 XML 文件所在檔案的 URL。該 URL 可以是本機檔案或 HTTP URL（[Web](../../../system.web/) 位址）。 |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) 方法

從指定的串流載入 XML 文件。

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 載入之 XML 文件的串流。 |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) 方法

從指定的 TextReader 載入 XML 文件。

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | 用於將 XML 資料輸入文件的 TextReader。 |

## XmlDocument::Load(SharedPtr\<XmlReader\>) 方法

從指定的 [XmlReader](../../xmlreader/) 載入 XML 文件。

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | 用於將 XML 資料輸入文件的 [XmlReader](../../xmlreader/)。 |

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [XmlDocument](../)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [TextReader](../../../system.io/textreader/)
* 類別 [XmlReader](../../xmlreader/)
* 名稱空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)