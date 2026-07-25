---
title: ToChar()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから開始する、指定された配列の 2 バイトを char_t 値に変換します。
type: docs
weight: 40
url: /ja/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) メソッド

指定されたインデックスから開始する、指定された配列の 2 バイトを char_t 値に変換します。

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) バイトを変換する配列 |
| startIndex | int | [Index](../../index/) 配列内でバイトの変換を開始するインデックス |

### 戻り値

変換結果の char_t 値

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) メソッド

指定されたインデックスから開始する、指定された配列の 2 バイトを char_t 値に変換します。

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | バイトを変換する ArrayView |
| startIndex | int | [Index](../../index/) 配列内でバイトの変換を開始するインデックス |

### 戻り値

変換結果の char_t 値

## 関連項目

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [BitConverter](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)