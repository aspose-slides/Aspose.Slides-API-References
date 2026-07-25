---
title: get_Encoding()
second_title: Aspose.Slides for C++ API リファレンス
description: XML ドキュメントのエンコーディングレベルを返します。
type: docs
weight: 14
url: /ja/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() メソッド

XML ドキュメントのエンコーディングレベルを返します。

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### 戻り値

有効な文字エンコーディング名。

## 備考

XML で最も一般的にサポートされている文字エンコーディング名は次のとおりです。

| カテゴリ | エンコーディング名 |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (「n」は 1 から 9 の数字) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

この値はオプションです。値が設定されていない場合、このメソッドは [String::Empty](../../../system/string/empty/) を返します。エンコーディング属性が含まれていない場合、ドキュメントが書き込まれるまたは保存されるときは UTF-8 エンコーディングが想定されます。

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XmlDeclaration](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)