---
title: GetByteCount()
second_title: Aspose.Slides for C++ API リファレンス
description: バッファをエンコードするために必要なバイト数を取得します。
type: docs
weight: 40
url: /ja/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) メソッド

バッファをエンコードするために必要なバイト数を取得します。

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコードする文字。 |
| index | int | [Buffer](../../../system/buffer/) オフセット。 |
| count | int | エンコードする文字数。 |
| flush | **bool** | true の場合、計算後にエンコーダの内部状態をクリアします。 |

### 戻り値

バッファをエンコードするために必要なバイト数。

## Encoder::GetByteCount(const char_t *, int, bool) メソッド

バッファをエンコードするために必要なバイト数を取得します。

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | エンコードする文字。 |
| count | int | エンコードする文字数。 |
| flush | **bool** | true の場合、計算後にエンコーダの内部状態をクリアします。 |

### 戻り値

バッファをエンコードするために必要なバイト数。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [Encoder](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)