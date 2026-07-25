---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在スコープ内にある、定義されたプレフィックスと名前空間のマッピングのコレクションを返します。
type: docs
weight: 1
url: /ja/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) メソッド

現在スコープにある、定義されたプレフィックスと名前空間のマッピングのコレクションを返します。

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 返す名前空間ノードの種類を指定する XmlNamespaceScope 値です。 |

### 戻り値

現在のスコープ内にある名前空間を含む IDictionary コレクション。

## 参照

* 列挙型 [XmlNamespaceScope](../../xmlnamespacescope/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IDictionary](../../../system.collections.generic/idictionary/)
* クラス [String](../../../system/string/)
* クラス [IXmlNamespaceResolver](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)