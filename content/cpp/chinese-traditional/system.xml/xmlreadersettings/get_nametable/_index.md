---
title: get_NameTable()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回用於原子化字串比較的 XmlNameTable。
type: docs
weight: 1
url: /zh-hant/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() 方法


返回用於原子化字串比較的 [XmlNameTable](../../xmlnametable/)。

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### 返回值

[XmlNameTable](../../xmlnametable/)，儲存所有由此 [XmlReaderSettings](../) 物件建立的 [XmlReader](../../xmlreader/) 實例使用的原子化字串。預設為 **nullptr**。如果此值為 **nullptr**，則建立的 [XmlReader](../../xmlreader/) 實例將使用新的空的 [NameTable](../../nametable/)。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNameTable](../../xmlnametable/)
* 類別 [XmlReaderSettings](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)