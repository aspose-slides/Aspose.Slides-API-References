---
title: get_LocalName()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードのローカル名を返します。
type: docs
weight: 27
url: /ja/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() メソッド

現在のノードのローカル名を返します。

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### 戻り値

プレフィックスが除去された現在のノードの名前です。たとえば、**LocalName** は要素 **<bk:book>** に対して **book** です。名前を持たないノードタイプ（**[Text](../../../system.text/)**、**Comment** など）に対しては、このメソッドは [String::Empty](../../../system/string/empty/) を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)