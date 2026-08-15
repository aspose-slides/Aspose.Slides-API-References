---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 將 XPathNavigator 移動到具有匹配本地名稱和命名空間 URI 的屬性。
type: docs
weight: 495
url: /zh-hant/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute(String, String) 方法

將 [XPathNavigator](../) 移動到具有匹配本地名稱和命名空間 URI 的屬性。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI；對於空命名空間，為 **nullptr**。 |

### 返回值

**true** 如果 [XPathNavigator](../) 成功移動到屬性；否則為 **false**。如果 **false**，[XPathNavigator](../) 的位置保持不變。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)