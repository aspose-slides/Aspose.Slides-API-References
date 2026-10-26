---
title: XmlNamespaceScope
second_title: Aspose.Slides for C++ API リファレンス
description: 名前空間のスコープを定義します。
type: docs
weight: 794
url: /ja/system.xml/xmlnamespacescope/
---
## XmlNamespaceScope 列挙型

名前空間のスコープを定義します。

```cpp
enum class XmlNamespaceScope
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| All | 0 | 現在のノードのスコープで定義されているすべての名前空間です。この中には常に暗黙的に宣言される xmlns:xml 名前空間が含まれます。返される名前空間の順序は定義されていません。 |
| ExcludeXml | 1 | 現在のノードのスコープで定義されているすべての名前空間（常に暗黙的に宣言される xmlns:xml 名前空間を除く）です。返される名前空間の順序は定義されていません。 |
| Local | 2 | 現在のノードでローカルに定義されているすべての名前空間です。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)