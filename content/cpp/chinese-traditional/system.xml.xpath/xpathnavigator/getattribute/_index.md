---
title: GetAttribute()
second_title: Aspose.Slides C++ 版 API 參考
description: 傳回具有指定本機名稱和命名空間 URI 的屬性值。
type: docs
weight: 482
url: /zh-hant/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) 方法

返回具有指定本機名稱和命名空間 URI 的屬性值。

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本機名稱。**localName** 是區分大小寫的。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 回傳值

一個 [String](../../../system/string/) 包含指定屬性的值；如果未找到匹配的屬性，或 [XPathNavigator](../) 未位於元素節點上，則返回 [String::Empty](../../../system/string/empty/)。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)