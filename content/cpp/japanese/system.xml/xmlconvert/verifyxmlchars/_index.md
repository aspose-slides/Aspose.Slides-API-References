---
title: VerifyXmlChars()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列引数内のすべての文字およびサロゲートペア文字が有効な XML 文字である場合は、渡された文字列を返します。それ以外の場合は、最初に検出された無効な文字に関する情報を含む XmlException がスローされます。
type: docs
weight: 105
url: /ja/system.xml/xmlconvert/verifyxmlchars/
---
## XmlConvert::VerifyXmlChars(const String\&) メソッド

文字列引数内のすべての文字およびサロゲートペア文字が有効な XML 文字である場合は、渡された文字列を返します。それ以外の場合は、最初に検出された無効な文字に関する情報を含む XmlException がスローされます。

```cpp
static String System::Xml::XmlConvert::VerifyXmlChars(const String &content)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| content | const [String](../../../system/string/)\& | [String](../../../system/string/) で、検証対象の文字を含みます。 |

### 戻り値

文字列引数内のすべての文字およびサロゲートペア文字が有効な XML 文字である場合は、渡された文字列を返します。それ以外の場合は、最初に検出された無効な文字に関する情報を含む XmlException がスローされます。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlConvert](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)