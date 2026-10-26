---
title: ToUInt64()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから開始して、指定された配列の 8 バイトを符号なし 64 ビット整数値に変換します。
type: docs
weight: 118
url: /ja/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) メソッド

指定されたインデックスから開始して、指定された配列の 8 バイトを符号なし 64 ビット整数値に変換します。

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) バイトを変換するために含む |
| startIndex | int | [Index](../../index/) 配列内で変換のためにバイトを取得し始めるインデックス |

### 戻り値

変換結果として得られる符号なし 64 ビット整数値

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) メソッド

指定されたインデックスから開始して、指定された配列の 8 バイトを符号なし 64 ビット整数値に変換します。

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | バイトを変換するために含む ArrayView |
| startIndex | int | [Index](../../index/) 配列内で変換のためにバイトを取得し始めるインデックス |

### 戻り値

変換結果として得られる符号なし 64 ビット整数値

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)