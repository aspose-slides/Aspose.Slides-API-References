---
title: ToInt16()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから開始する、指定された配列の2バイトを 16 ビット整数値に変換します。
type: docs
weight: 53
url: /ja/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) method


指定されたインデックスから開始する、指定された配列の2バイトを 16 ビット整数値に変換します。

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) は変換対象のバイトを含みます |
| startIndex | int | [Index](../../index/) は変換のためにバイトの取得を開始する配列内のインデックスです |

### 戻り値

変換から得られる 16 ビット整数値

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) method


指定されたインデックスから開始する、指定された配列の2バイトを 16 ビット整数値に変換します。

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 変換するバイトを含む ArrayView |
| startIndex | int | [Index](../../index/) は変換のためにバイトの取得を開始する配列内のインデックスです |

### 戻り値

変換から得られる 16 ビット整数値

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [BitConverter](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)