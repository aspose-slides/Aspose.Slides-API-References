---
title: get_LocalName()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードのローカル名を返します。
type: docs
weight: 27
url: /ja/system.xml/xmltextreader/get_localname/
---
## XmlTextReader::get_LocalName() メソッド


現在のノードのローカル名を返します。

```cpp
String System::Xml::XmlTextReader::get_LocalName() override
```


### 戻り値

プレフィックスが除かれた現在のノードの名前です。例えば、**LocalName** は要素 **<bk:book>** の場合 **book** です。名前を持たないノードタイプ（**[Text](../../../system.text/)**、**Comment** など）に対しては、このメソッドは [String::Empty](../../../system/string/empty/) を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)