---
title: ToBoolean()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから開始する配列の 1 バイトを論理値に変換します。
type: docs
weight: 27
url: /ja/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) メソッド

指定されたインデックスから開始する配列の 1 バイトを論理値に変換します。

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) バイトを変換するために含む |
| startIndex | int | [Index](../../index/) 配列内で変換のためにバイトを取得し始めるインデックス |

### 戻り値

[Boolean](../../boolean/) 変換から得られる値

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) メソッド

指定されたインデックスから開始する配列の 1 バイトを論理値に変換します。

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView バイトを変換するために含む |
| startIndex | int | [Index](../../index/) 配列内で変換のためにバイトを取得し始めるインデックス |

### 戻り値

[Boolean](../../boolean/) 変換から得られる値

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [BitConverter](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)