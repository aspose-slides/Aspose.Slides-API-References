---
title: ReadToDescendant()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 XmlReader 前進至帶有指定限定名稱的下一個子孫元素。
type: docs
weight: 911
url: /zh-hant/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) 方法

將 [XmlReader](../) 前進至帶有指定限定名稱的下一個子孫元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 您想要移動到的元素的限定名稱。 |

### 回傳值

**true** 如果找到匹配的子孫元素；否則 **false**。如果未找到匹配的子元素，[XmlReader](../) 會定位在元素的結束標記（[XmlReader::get_NodeType](../get_nodetype/) 值為 [XmlNodeType::EndElement](../../xmlnodetype/)）上。若在呼叫 [XmlReader::ReadToDescendant(String)](./) 時 [XmlReader](../) 未定位在任何元素上，此 方法 回傳 **false**，且 [XmlReader](../) 的位置不會變更。

## XmlReader::ReadToDescendant(String, String) 方法

將 [XmlReader](../) 前進至具備指定本地名稱和命名空間 URI 的下一個子孫元素。

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 您想要移動到的元素的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 您想要移動到的元素的命名空間 URI。 |

### 回傳值

**true** 如果找到匹配的子孫元素；否則 **false**。如果未找到匹配的子元素，[XmlReader](../) 會定位在元素的結束標記（[XmlReader::get_NodeType](../get_nodetype/) 值為 [XmlNodeType::EndElement](../../xmlnodetype/)）上。若在呼叫 [XmlReader::ReadToDescendant(String,String)](./) 時 [XmlReader](../) 未定位在任何元素上，此 方法 回傳 **false**，且 [XmlReader](../) 的位置不會變更。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)