---
title: GetNamespaceOfPrefix()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードのスコープ内にある、指定されたプレフィックスに対する最も近い xmlns 宣言を検索し、その宣言に含まれる名前空間 URI を返します。
type: docs
weight: 560
url: /ja/system.xml/xmlnode/getnamespaceofprefix/
---
## XmlNode::GetNamespaceOfPrefix(String) メソッド

Looks up the closest **xmlns** declaration for the given prefix that is in scope for the current node and returns the namespace URI in the declaration.

```cpp
virtual String System::Xml::XmlNode::GetNamespaceOfPrefix(String prefix)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | 取得したい名前空間 URI のプレフィックスです。 |

### 戻り値

指定されたプレフィックスの名前空間 URI。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)