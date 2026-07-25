---
title: ToInt64()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された配列の指定インデックスから開始して8バイトを変換し、64ビット整数値を取得します。
type: docs
weight: 79
url: /ja/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) メソッド

指定された配列の指定インデックスから開始して8バイトを変換し、64ビット整数値を取得します。

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) が変換するバイトを含む |
| startIndex | int | [Index](../../index/) は配列内で変換のためにバイトを取り始めるインデックス |

### 戻り値

64ビット整数値

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) メソッド

指定された配列の指定インデックスから開始して8バイトを変換し、64ビット整数値を取得します。

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 変換するバイトを含むArrayView |
| startIndex | int | [Index](../../index/) は配列内で変換のためにバイトを取り始めるインデックス |

### 戻り値

64ビット整数値

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)