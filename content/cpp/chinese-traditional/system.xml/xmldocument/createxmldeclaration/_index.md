---
title: CreateXmlDeclaration()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立具有指定值的 XmlDeclaration 節點。
type: docs
weight: 378
url: /zh-hant/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) method

建立具有指定值的 [XmlDeclaration](../../xmldeclaration/) 節點。

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | 版本必須為 \"1.0\"。 |
| encoding | const [String](../../../system/string/)\& | 編碼屬性的值。此編碼用於將 [XmlDocument](../) 儲存至檔案或串流時；因此，必須設定為 [Text::Encoding](../../../system.text/encoding/) 類別支援的字串，否則 \"XmlDocument::Save(String)\" 失敗。如果此值為 **nullptr** 或 [String::Empty](../../../system/string/empty/)，[XmlDocument::Save](../save/) 方法不會在 XML 宣告上寫入編碼屬性，因而使用預設編碼 UTF-8。 |
| standalone | const [String](../../../system/string/)\& | 值必須為 \"yes\" 或 \"no\"。如果此值為 **nullptr** 或 [String::Empty](../../../system/string/empty/)，[XmlDocument::Save](../save/) 方法不會在 XML 宣告上寫入 standalone 屬性。 |

### 傳回值

新的 [XmlDeclaration](../../xmldeclaration/) 節點。

## 備註

Note: If the [XmlDocument](../) is saved to either a TextWriter or an [XmlTextWriter](../../xmltextwriter/), this encoding value is discarded. Instead, the encoding of the TextWriter or the [XmlTextWriter](../../xmltextwriter/) is used. This ensures that the XML written out can be read back using the correct encoding.

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlDeclaration](../../xmldeclaration/)
* 類別 [String](../../../system/string/)
* 類別 [XmlDocument](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)