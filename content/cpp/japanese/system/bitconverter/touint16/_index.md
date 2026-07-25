---
title: ToUInt16()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定されたインデックスから開始する、指定された配列の 2 バイトを符号なし 16 ビット整数値に変換します。
type: docs
weight: 92
url: /ja/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) メソッド


指定されたインデックスから開始する、指定された配列の 2 バイトを符号なし 16 ビット整数値に変換します。

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 変換するバイトを含む |
| startIndex | int | [Index](../../index/) 配列内で変換のためにバイトの取得を開始するインデックス |

### 戻り値

変換により得られる符号なし 16 ビット整数値

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) メソッド


指定されたインデックスから開始する、指定された配列の 2 バイトを符号なし 16 ビット整数値に変換します。

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 変換するバイトを含む |
| startIndex | int | [Index](../../index/) 配列内で変換のためにバイトの取得を開始するインデックス |

### 戻り値

変換により得られる符号なし 16 ビット整数値

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [BitConverter](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)