---
title: ToUInt32()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから開始する、指定された配列の 4 バイトを符号なし 32 ビット整数に変換します。
type: docs
weight: 105
url: /ja/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) method

指定されたインデックスから開始する、指定された配列の 4 バイトを符号なし 32 ビット整数に変換します。

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) バイトを変換するために含む |
| startIndex | int | [Index](../../index/) 配列内で変換用バイトの取得を開始するインデックス |

### 戻り値

変換により得られる符号なし 32 ビット整数値

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method

指定されたインデックスから開始する、指定された配列の 4 バイトを符号なし 32 ビット整数に変換します。

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | バイトを変換するために含む ArrayView |
| startIndex | int | [Index](../../index/) 配列内で変換用バイトの取得を開始するインデックス |

### 戻り値

変換により得られる符号なし 32 ビット整数値

## 関連項目

* タイプ定義 [ArrayPtr](../../arrayptr/)
* クラス [BitConverter](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)