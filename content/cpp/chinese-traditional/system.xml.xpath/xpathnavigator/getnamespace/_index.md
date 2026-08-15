---
title: GetNamespace()
second_title: Aspose.Slides for C++ API 參考
description: 傳回對應於指定本地名稱的命名空間節點的值。
type: docs
weight: 534
url: /zh-hant/system.xml.xpath/xpathnavigator/getnamespace/
---
## XPathNavigator::GetNamespace(String) 方法

傳回對應於指定本地名稱的命名空間節點的值。

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetNamespace(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 命名空間節點的本地名稱。 |

### 返回值

一個 [String](../../../system/string/)，其中包含命名空間節點的值；如果未找到匹配的命名空間節點，或如果 [XPathNavigator](../) 未定位在元素節點上，則為 [String::Empty](../../../system/string/empty/)。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 程式庫 [Aspose.Slides](../../../)