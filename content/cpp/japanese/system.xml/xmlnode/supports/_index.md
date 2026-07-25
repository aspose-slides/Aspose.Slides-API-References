---
title: Supports()
second_title: Aspose.Slides for C++ API リファレンス
description: DOM 実装が特定の機能を実装しているかどうかをテストします。
type: docs
weight: 482
url: /ja/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) メソッド

DOM 実装が特定の機能を実装しているかどうかをテストします。

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| feature | [String](../../../system/string/) | テストする機能のパッケージ名です。この名前は大文字と小文字を区別しません。 |
| version | [String](../../../system/string/) | テストするパッケージ名のバージョン番号です。バージョンが指定されていない場合 (null)、機能の任意のバージョンをサポートすることによりメソッドは **true** を返します。 |

### 戻り値

指定されたバージョンで機能が実装されている場合は **true**、それ以外の場合は **false** を返します。

## 備考

次の表は **true** を返す組み合わせを示しています。

| 機能 | [Version](../../../system/version/) |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)