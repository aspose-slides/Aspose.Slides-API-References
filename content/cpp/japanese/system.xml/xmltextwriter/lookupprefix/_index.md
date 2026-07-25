---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の名前空間スコープで定義された、namespace URI の最も近いプレフィックスを返します。
type: docs
weight: 508
url: /ja/system.xml/xmltextwriter/lookupprefix/
---
## XmlTextWriter::LookupPrefix(String) メソッド

現在の名前空間スコープで定義された、指定された namespace URI に最も近いプレフィックスを返します。

```cpp
String System::Xml::XmlTextWriter::LookupPrefix(String ns) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ns | [String](../../../system/string/) | プレフィックスを検索したい namespace URI。 |

### 戻り値

一致するプレフィックス。現在のスコープで一致する namespace URI が見つからない場合は **nullptr** が返されます。

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XmlTextWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)