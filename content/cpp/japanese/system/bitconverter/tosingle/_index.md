---
title: ToSingle()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから開始する、指定された配列の 4 バイトを単精度浮動小数点値に変換します。
type: docs
weight: 131
url: /ja/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) method

指定されたインデックスから開始する、指定された配列の 4 バイトを単精度浮動小数点値に変換します。

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 変換するバイトを含む |
| startIndex | int | [Index](../../index/) 配列内でバイトの取得を開始するインデックス |

### 戻り値

変換結果の単精度浮動小数点値

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) method

指定されたインデックスから開始する、指定された配列の 4 バイトを単精度浮動小数点値に変換します。

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 変換するバイトを含む |
| startIndex | int | [Index](../../index/) 配列内でバイトの取得を開始するインデックス |

### 戻り値

変換結果の単精度浮動小数点値

## 関連項目

* typedef [ArrayPtr](../../arrayptr/)
* クラス [BitConverter](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)