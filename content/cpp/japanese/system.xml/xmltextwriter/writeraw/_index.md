---
title: WriteRaw()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字バッファから手動で生のマークアップを書き込みます。
type: docs
weight: 417
url: /ja/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) メソッド

文字バッファから手動で生のマークアップを書き込みます。

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | 書き込むテキストを含む文字配列。 |
| index | **int32_t** | 書き込むテキストの開始位置を示すバッファ内の位置。 |
| count | **int32_t** | 書き込む文字数。 |

## XmlTextWriter::WriteRaw(const String\&) メソッド

文字列から手動で生のマークアップを書き込みます。

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/)（書き込むテキストを含む）。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlTextWriter](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)