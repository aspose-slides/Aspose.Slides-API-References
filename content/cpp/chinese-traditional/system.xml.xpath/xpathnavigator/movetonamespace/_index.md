---
title: MoveToNamespace()
second_title: Aspose.Slides for C++ API 參考
description: 將 XPathNavigator 移動到具有指定命名空間前綴的命名空間節點。
type: docs
weight: 547
url: /zh-hant/system.xml.xpath/xpathnavigator/movetonamespace/
---
## XPathNavigator::MoveToNamespace(String) 方法

將 [XPathNavigator](../) 移動到具有指定命名空間前綴的命名空間節點。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNamespace(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 命名空間節點的命名空間前綴。 |

### 傳回值

**true** 如果 [XPathNavigator](../) 成功移動到指定的命名空間；**false** 如果未找到匹配的命名空間節點，或 [XPathNavigator](../) 未位於元素節點上。若 **false**，[XPathNavigator](../) 的位置保持不變。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)