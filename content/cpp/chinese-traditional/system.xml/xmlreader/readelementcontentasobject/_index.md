---
title: ReadElementContentAsObject()
second_title: Aspose.Slides for C++ API 參考
description: 讀取目前元素，並將內容作為 Object 傳回。
type: docs
weight: 469
url: /zh-hant/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() 方法

讀取目前元素，並將內容作為 [Object](../../../system/object/) 傳回。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### 返回值

最適合類型的盒裝物件。[XmlReader::get_ValueType](../get_valuetype/) 值決定適當的類型。如果內容被指定為列表類型，則此方法會傳回適當類型的盒裝物件陣列。

## XmlReader::ReadElementContentAsObject(String, String) 方法

檢查指定的本地名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為 [Object](../../../system/object/) 傳回。

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 元素的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 元素的命名空間 URI。 |

### 返回值

最適合類型的盒裝物件。[XmlReader::get_ValueType](../get_valuetype/) 值決定適當的類型。如果內容被指定為列表類型，則此方法會傳回適當類型的盒裝物件陣列。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [XmlReader](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)