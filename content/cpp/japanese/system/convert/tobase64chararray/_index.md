---
title: ToBase64CharArray()
second_title: Aspose.Slides for C++ API リファレンス
description: Base-64 は、指定されたバイト配列の要素範囲をエンコードし、エンコードされたデータを Unicode 文字の配列として格納します。
type: docs
weight: 27
url: /ja/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) メソッド

Base-64 は、指定されたバイト配列の要素範囲をエンコードし、エンコードされたデータを Unicode 文字の配列として格納します。

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | エンコードする要素範囲を含むバイト配列 |
| offset_in | int | 入力配列内でエンコード範囲が開始する要素のインデックス |
| length | int | エンコードする要素範囲の長さ |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | 結果データを格納する出力配列への定数参照 |
| offset_out | int | 結果データの格納を開始する出力配列内のインデックス |
| insert_line_breaks | **bool** | 76 文字ごとに改行文字を出力配列に挿入するかどうかを指定 |

### 戻り値

出力配列に書き込まれた文字の数

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) メソッド

Base-64 は、指定されたバイト配列の要素範囲をエンコードし、エンコードされたデータを Unicode 文字の配列として格納します。

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | エンコードする要素範囲を含むバイト配列 |
| offset_in | int | 入力配列内でエンコード範囲が開始する要素のインデックス |
| length | int | エンコードする要素範囲の長さ |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 結果データを格納する出力配列への定数参照 |
| offset_out | int | 結果データの格納を開始する出力配列内のインデックス |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Base-64 エンコードデータの書式設定オプションを指定 |

### 戻り値

出力配列に書き込まれた文字の数

## 参考

* 列挙型 [Base64FormattingOptions](../../base64formattingoptions/)
* 型定義 [ArrayPtr](../../arrayptr/)
* 構造体 [Convert](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)