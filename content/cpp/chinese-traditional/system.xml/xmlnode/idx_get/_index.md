---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考文件
description: "傳回具有指定 XmlNode::get_Name 的第一個子元素。"
type: docs
weight: 586
url: /zh-hant/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) 方法

傳回具有指定 [XmlNode::get_Name](../get_name/) 的第一個子元素。

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要檢索之元素的限定名稱。 |

### 傳回值

第一個符合指定名稱的 [XmlElement](../../xmlelement/)。如果沒有匹配項，則傳回 **nullptr**。

## XmlNode::idx_get(String, String) 方法

傳回具有指定 [XmlNode::get_LocalName](../get_localname/) 與 [XmlNode::get_NamespaceURI](../get_namespaceuri/) 值的第一個子元素。

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 元素的本地名稱。 |
| ns | [String](../../../system/string/) | 元素的命名空間 URI。 |

### 傳回值

第一個符合 **localname** 與 **ns** 的 [XmlElement](../../xmlelement/)。如果沒有匹配項，則傳回 **nullptr**。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlElement](../../xmlelement/)
* 類別 [String](../../../system/string/)
* 類別 [XmlNode](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)