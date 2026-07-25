---
title: ToInt32()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された配列の指定インデックスから開始して、4 バイトを 32 ビット整数値に変換します。
type: docs
weight: 66
url: /ja/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) method


指定された配列の指定インデックスから開始して、4 バイトを 32 ビット整数値に変換します。

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 変換するバイトを含む |
| startIndex | int | [Index](../../index/) 配列内でバイトの取得を開始するインデックス |

### 戻り値

32 ビット整数値 (変換結果)

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method


指定された配列の指定インデックスから開始して、4 バイトを 32 ビット整数値に変換します。

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 変換するバイトを含む ArrayView |
| startIndex | int | [Index](../../index/) 配列内でバイトの取得を開始するインデックス |

### 戻り値

32 ビット整数値 (変換結果)

## 参照

* typedef [ArrayPtr](../../arrayptr/)
* クラス [BitConverter](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)