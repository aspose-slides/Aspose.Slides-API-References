---
title: get_LocalName()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、現在のノードのローカル名を取得します。
type: docs
weight: 40
url: /ja/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() メソッド

派生クラスでオーバーライドされた場合、現在のノードのローカル名を取得します。

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### 戻り値

プレフィックスが除かれた現在のノードの名前です。たとえば、要素 **<bk:book>** の **LocalName** は **book** です。名前を持たないノードタイプ（**[Text](../../../system.text/)**、**Comment** など）の場合、このメソッドは [String::Empty](../../../system/string/empty/) を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)