---
title: ToString()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたバイト配列のすべての値を16進数文字列に変換します。16進表記で使用する文字の大文字小文字および隣接するバイトのペア間に挿入される区切り文字は、対応する引数で指定されます。
type: docs
weight: 157
url: /ja/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) メソッド

指定されたバイト配列のすべての値を16進数文字列に変換します。16進表記で使用する文字の大文字小文字、および隣接するバイトのペア間に挿入される区切り文字は、対応する引数で指定されます。

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) バイトを変換するために含む |
| uppercase | **bool** | 結果の16進表記で使用する文字の大文字小文字を指定します |
| separator | const [String](../../string/)\& | 結果文字列で隣接するバイトのペア間に挿入される区切り文字として使用される文字列 |

### 戻り値

[String](../../string/) 指定されたバイト配列の16進表記を含む

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) メソッド

指定されたインデックスから開始して、指定されたバイト配列の値を16進数文字列に変換します。

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) バイトを変換するために含む |
| startIndex | int | [Index](../../index/) 変換を開始する指定された配列内のインデックス |

### 戻り値

[String](../../string/) 指定された配列の指定範囲の要素の16進表記を含む

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) メソッド

指定されたバイト配列の範囲内の値を16進数文字列に変換します。

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) バイトを変換するために含む |
| startIndex | int | [Index](../../index/) 変換対象のバイト配列要素の範囲が開始する指定された配列内のインデックス |
| length | int | 変換対象のバイト配列要素の範囲の長さ |

### 戻り値

[String](../../string/) 指定された配列の指定範囲の要素の16進表記を含む

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* クラス [String](../../string/)
* クラス [BitConverter](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)