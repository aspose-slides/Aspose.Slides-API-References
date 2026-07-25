---
title: FromBase64CharArray()
second_title: Aspose.Slides for C++ API リファレンス
description: Unicode 文字の配列内の範囲として表現された base-64 エンコードデータをデコードします。
type: docs
weight: 53
url: /ja/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) メソッド


Unicode 文字の配列内の範囲として表現された base-64 エンコードデータをデコードします。

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | デコードするデータを含む配列 |
| offset | int | デコードする範囲が始まる入力配列内の位置 |
| length | int | デコードする範囲の長さ |

### 戻り値

デコードされたデータを含むバイト配列

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* 構造体 [Convert](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)