---
title: ToDouble()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから開始する、指定された配列の 8 バイトを倍精度浮動小数点値に変換します。
type: docs
weight: 144
url: /ja/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) メソッド


指定されたインデックスから開始する、指定された配列の 8 バイトを倍精度浮動小数点値に変換します。

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 変換するバイトを含む |
| startIndex | int | [Index](../../index/) 配列内でバイト変換を開始するインデックス |

### 戻り値

変換結果の倍精度浮動小数点値

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) メソッド


指定されたインデックスから開始する、指定された配列の 8 バイトを倍精度浮動小数点値に変換します。

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 変換するバイトを含む ArrayView |
| startIndex | int | [Index](../../index/) 配列内でバイト変換を開始するインデックス |

### 戻り値

変換結果の倍精度浮動小数点値

## 参照

* typedef [ArrayPtr](../../arrayptr/)
* クラス [BitConverter](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)