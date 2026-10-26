---
title: XPathNamespaceScope
second_title: Aspose.Slides for C++ API リファレンス
description: 名前空間のスコープを定義します。
type: docs
weight: 144
url: /ja/system.xml.xpath/xpathnamespacescope/
---
## XPathNamespaceScope 列挙型

名前空間のスコープを定義します。

```cpp
enum class XPathNamespaceScope
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| All | 0 | 現在のノードのスコープで定義されているすべての名前空間を返します。これは常に暗黙的に宣言される **xmlns:xml** 名前空間を含みます。返される名前空間の順序は定義されていません。 |
| ExcludeXml | 1 | 現在のノードのスコープで定義されているすべての名前空間を返しますが、**xmlns:xml** 名前空間は除外します。**xmlns:xml** 名前空間は常に暗黙的に宣言されます。返される名前空間の順序は定義されていません。 |
| Local | 2 | 現在のノードでローカルに定義されているすべての名前空間を返します。 |

## 参照

* 名前空間 [System::Xml::XPath](../)
* ライブラリ [Aspose.Slides](../../)