---
title: ToBase64String()
second_title: Aspose.Slides for C++ API リファレンス
description: Base-64 は、指定されたバイト配列の要素をエンコードし、エンコードされたデータを文字列として返します。
type: docs
weight: 40
url: /ja/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) メソッド

Base-64 は指定されたバイト配列の要素をエンコードし、エンコードされたデータを文字列として返します。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | エンコードするバイト配列 |
| insert_line_breaks | **bool** | 出力文字列に 76 文字ごとに改行文字を挿入するかどうかを指定します |

### 戻り値

入力配列の Base-64 エンコード表現を含む文字列

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) メソッド

Base-64 は指定されたバイト配列の一定範囲の要素をエンコードし、エンコードされたデータを文字列として返します。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | エンコードする要素の範囲が含まれるバイト配列 |
| offset_in | int | エンコード範囲が開始する入力配列の要素インデックス |
| length | int | エンコードする要素範囲の長さ |
| insert_line_breaks | **bool** | 出力文字列に 76 文字ごとに改行文字を挿入するかどうかを指定します |

### 戻り値

入力配列の要素範囲の Base-64 エンコード表現を含む文字列

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) メソッド

Base-64 は指定されたバイト配列の要素をエンコードし、エンコードされたデータを文字列として返します。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | エンコードするバイト配列 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 エンコードデータの書式設定オプションを指定します |

### 戻り値

入力配列の Base-64 エンコード表現を含む文字列

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) メソッド

Base-64 は指定されたバイト配列の一定範囲の要素をエンコードし、エンコードされたデータを文字列として返します。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | エンコードする要素の範囲が含まれるバイト配列 |
| offset_in | int | エンコード範囲が開始する入力配列の要素インデックス |
| length | int | エンコードする要素範囲の長さ |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 エンコードデータの書式設定オプションを指定します |

### 戻り値

入力配列の要素範囲の Base-64 エンコード表現を含む文字列

## 参照

* 列挙 [Base64FormattingOptions](../../base64formattingoptions/)
* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [String](../../string/)
* 構造体 [Convert](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)