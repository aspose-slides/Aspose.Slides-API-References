---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、現在の名前空間スコープで定義された名前空間 URI に対する最も近いプレフィックスを返します。
type: docs
weight: 352
url: /ja/system.xml/xmlwriter/lookupprefix/
---
## XmlWriter::LookupPrefix(String) メソッド


派生クラスでオーバーライドされた場合、名前空間 URI に対して現在の名前空間スコープで定義されている最も近いプレフィックスを返します。

```cpp
virtual String System::Xml::XmlWriter::LookupPrefix(String ns)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| ns | [String](../../../system/string/) | プレフィックスを検索したい名前空間 URI。 |

### 戻り値

一致するプレフィックス、または現在のスコープに一致する名前空間 URI が見つからない場合は **nullptr** を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)