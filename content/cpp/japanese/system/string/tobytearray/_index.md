---
title: ToByteArray()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列または部分文字列をバイト配列に変換します。
type: docs
weight: 508
url: /ja/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const メソッド

文字列または部分文字列をバイト配列に変換します。

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | **int32_t** | 部分文字列の開始インデックスです。 |
| length | **int32_t** | 部分文字列の長さです。 |
| LE | **bool** | true の場合、リトルエンディアンで文字をエンコードします。false の場合はビッグエンディアンを使用します。 |

### 戻り値

[Array](../../array/) 文字列の文字を表すバイトを含む。

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)