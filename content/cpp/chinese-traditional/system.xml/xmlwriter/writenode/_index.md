---
title: WriteNode()
second_title: Aspose.Slides for C++ API 參考
description: 在衍生類別中覆寫時，會將讀取器的所有內容複製到寫入器，並將讀取器移動到下一個同級節點的開始位置。
type: docs
weight: 430
url: /zh-hant/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) 方法

當在衍生類別中覆寫時，會將讀取器中的所有內容複製到寫入器，並將讀取器移動到下一個同級節點的開始位置。

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | 要讀取的 [XmlReader](../../xmlreader/)。 |
| defattr | **bool** | **true** 用於從 [XmlReader](../../xmlreader/) 複製預設屬性；否則為 **false**。 |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) 方法

將 XPathNavigator 物件的所有內容複製到寫入器。XPathNavigator 的位置保持不變。

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 要複製的 XPathNavigator。 |
| defattr | **bool** | **true** 用於複製預設屬性；否則為 **false**。 |

## 另見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlReader](../../xmlreader/)
* 類別 [XmlWriter](../)
* 類別 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)