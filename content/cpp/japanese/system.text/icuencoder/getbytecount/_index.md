---
title: GetByteCount()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: バッファをエンコードするために必要なバイト数を取得します。
type: docs
weight: 40
url: /ja/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method

バッファをエンコードするために必要なバイト数を取得します。

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | エンコードする文字。 |
| index | int | [Buffer](../../../system/buffer/) オフセット。 |
| count | int | エンコードする文字数。 |
| flush | **bool** | true の場合、計算後に内部エンコーダ状態をクリアします。 |

### Return Value

バッファをエンコードするために必要なバイト数。

## ICUEncoder::GetByteCount(const char_t *, int, bool) method

バッファをエンコードするために必要なバイト数を取得します。

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | エンコードする文字。 |
| count | int | エンコードする文字数。 |
| flush | **bool** | true の場合、計算後に内部エンコーダ状態をクリアします。 |

### Return Value

バッファをエンコードするために必要なバイト数。

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [ICUEncoder](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)