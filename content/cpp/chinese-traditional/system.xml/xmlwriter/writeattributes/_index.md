---
title: WriteAttributes()
second_title: Aspose.Slides for C++ API 參考手冊
description: 當在派生類別中被覆寫時，會寫出在 XmlReader 中目前位置找到的所有屬性。
type: docs
weight: 417
url: /zh-hant/system.xml/xmlwriter/writeattributes/
---
## XmlWriter::WriteAttributes(SharedPtr\<XmlReader\>, bool) 方法


當在派生類別中被覆寫時，會寫出在 [XmlReader](../../xmlreader/) 中目前位置找到的所有屬性。

```cpp
virtual void System::Xml::XmlWriter::WriteAttributes(SharedPtr<XmlReader> reader, bool defattr)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | 用於複製屬性的 [XmlReader](../../xmlreader/)。 |
| defattr | **bool** | **true** 用於從 [XmlReader](../../xmlreader/) 複製預設屬性；否則為 **false**。 |

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlReader](../../xmlreader/)
* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)