---
title: CanDeserialize()
second_title: Aspose.Slides for C++ API 參考
description: 檢查指定的讀取器是否處於可反序列化狀態。
type: docs
weight: 1
url: /zh-hant/system.xml.serialization/xmlserializer/candeserialize/
---
## XmlSerializer::CanDeserialize(System::SharedPtr\<XmlReader\>) 方法

檢查指定的讀取器是否處於可反序列化狀態。

```cpp
virtual bool System::Xml::Serialization::XmlSerializer::CanDeserialize(System::SharedPtr<XmlReader> xmlReader)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 需要檢查的讀取器。 |

### 返回值

若 xmlReader 可以被反序列化則回傳 true，否則回傳 false。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlReader](../../../system.xml/xmlreader/)
* 類別 [XmlSerializer](../)
* 命名空間 [System::Xml::Serialization](../../)
* 函式庫 [Aspose.Slides](../../../)