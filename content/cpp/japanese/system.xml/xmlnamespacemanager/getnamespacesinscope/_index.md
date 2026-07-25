---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のスコープにある名前空間を列挙するために使用できる、プレフィックスでキー付けされた名前空間名のコレクションを返します。
type: docs
weight: 105
url: /ja/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) メソッド


現在のスコープにある名前空間を列挙するために使用できる、プレフィックスでキー付けされた名前空間名のコレクションを返します。

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 返される名前空間ノードのタイプを指定する列挙値です。 |

### 戻り値

現在のスコープにある名前空間とプレフィックスのペアのコレクションです。

## 参照

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)