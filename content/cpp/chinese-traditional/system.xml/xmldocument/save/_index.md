---
title: Save()
second_title: Aspose.Slides for C++ API 參考
description: 將 XML 文件保存到指定的檔案。如果指定的檔案已存在，此方法會覆寫它。
type: docs
weight: 534
url: /zh-hant/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) 方法

將 XML 文件保存到指定的檔案。如果指定的檔案已存在，此方法會覆寫它。

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | [String](../../../system/string/) | 您要儲存文件的檔案位置。 |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) 方法

將 XML 文件保存到指定的串流。

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | 您要儲存的串流。 |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) 方法

將 XML 文件保存到指定的 TextWriter。

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | 您要儲存的 TextWriter。 |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) 方法

將 XML 文件保存到指定的 [XmlWriter](../../xmlwriter/)。

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | 您要儲存的 [XmlWriter](../../xmlwriter/)。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [XmlDocument](../)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [TextWriter](../../../system.io/textwriter/)
* 類別 [XmlWriter](../../xmlwriter/)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)