---
title: XmlTextWriter()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的串流和編碼建立 XmlTextWriter 類別的實例。
type: docs
weight: 183
url: /zh-hant/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) 建構函式

使用指定的串流和編碼建立 [XmlTextWriter](../) 類別的實例。

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | 您想要寫入的串流。 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要產生的編碼。如果 encoding 為 **nullptr**，則以 UTF-8 輸出串流，並從 **ProcessingInstruction** 中省略 encoding 屬性。 |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) 建構函式

使用指定的檔案建立 [XmlTextWriter](../) 類別的實例。

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 要寫入的檔案名稱。如果檔案已存在，將截斷它並以新內容覆寫。 |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 要產生的編碼。如果 encoding 為 **nullptr**，則以 UTF-8 輸出檔案，並從 **ProcessingInstruction** 中省略 encoding 屬性。 |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) 建構函式

使用指定的 TextWriter 建立 [XmlTextWriter](../) 類別的實例。

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | 要寫入的 TextWriter。假設該 TextWriter 已設定為正確的編碼。 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [Encoding](../../../system.text/encoding/)
* 類別 [XmlTextWriter](../)
* 類別 [String](../../../system/string/)
* 類別 [TextWriter](../../../system.io/textwriter/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)