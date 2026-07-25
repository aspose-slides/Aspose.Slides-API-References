---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在スコープにあるすべての名前空間を含むコレクションを返します。
type: docs
weight: 716
url: /ja/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) メソッド

現在スコープにあるすべての名前空間を含むコレクションを返します。

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | XmlNamespaceScope の値で、返す名前空間ノードのタイプを指定します。 |

### 戻り値

現在スコープにあるすべての名前空間を含む IDictionary オブジェクトです。リーダーが要素上に位置していない場合、空のディクショナリ（名前空間なし）が返されます。

## 関連項目

* 列挙体 [XmlNamespaceScope](../../xmlnamespacescope/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IDictionary](../../../system.collections.generic/idictionary/)
* クラス [String](../../../system/string/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)