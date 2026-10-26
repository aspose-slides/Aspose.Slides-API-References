---
title: get_IndentChars()
second_title: Aspose.Slides for C++ API リファレンス
description: "インデント時に使用する文字列を返します。この設定は XmlWriterSettings::set_Indent の値が true に設定されているときに使用されます。"
type: docs
weight: 131
url: /ja/system.xml/xmlwritersettings/get_indentchars/
---
## XmlWriterSettings::get_IndentChars() メソッド

インデント時に使用する文字列を返します。この設定は、[XmlWriterSettings::set_Indent](../set_indent/) の値が **true** に設定されているときに使用されます。

```cpp
String System::Xml::XmlWriterSettings::get_IndentChars()
```

### 戻り値

インデント時に使用する文字列です。任意の文字列値を設定できます。ただし、XML の有効性を保つために、スペース文字、タブ、キャリッジリターン、または改行などの有効な空白文字のみを指定すべきです。デフォルトはスペース2つです。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlWriterSettings](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)