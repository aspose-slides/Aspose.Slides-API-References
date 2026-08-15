---
title: XPathNamespaceScope
second_title: Aspose.Slides C++ API 參考文件
description: 定義命名空間範圍。
type: docs
weight: 144
url: /zh-hant/system.xml.xpath/xpathnamespacescope/
---
## XPathNamespaceScope 列舉


定義命名空間範圍。

```cpp
enum class XPathNamespaceScope
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| All | 0 | 返回在目前節點範圍內定義的所有命名空間。這包括 **xmlns:xml** 命名空間，該命名空間總是隱式宣告。返回的命名空間順序未定義。 |
| ExcludeXml | 1 | 返回在目前節點範圍內定義的所有命名空間，但不包括 **xmlns:xml** 命名空間。**xmlns:xml** 命名空間總是隱式宣告。返回的命名空間順序未定義。 |
| Local | 2 | 返回在目前節點本地定義的所有命名空間。 |

## 另請參閱

* 命名空間 [System::Xml::XPath](../)
* 函式庫 [Aspose.Slides](../../)