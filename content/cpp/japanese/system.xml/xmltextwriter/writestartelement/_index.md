---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された開始タグを書き込み、指定された名前空間とプレフィックスに関連付けます。
type: docs
weight: 235
url: /ja/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) method

指定された開始タグを書き込み、指定された名前空間とプレフィックスに関連付けます。

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要素の名前空間プレフィックス。 |
| localName | const [String](../../../system/string/)\& | 要素のローカル名。 |
| ns | const [String](../../../system/string/)\& | 要素に関連付ける名前空間 URI。 この名前空間がすでにスコープ内にあり、関連付けられたプレフィックスがある場合、ライターはそのプレフィックスも自動的に書き込みます。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlTextWriter](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)