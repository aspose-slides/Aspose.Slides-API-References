---
title: PtrToStringAuto()
second_title: Aspose.Slides for C++ API リファレンス
description: アンマネージドのゼロ終端文字列から管理対象の String を作成します。
type: docs
weight: 287
url: /ja/system.runtime.interopservices/marshal/ptrtostringauto/
---
## Marshal::PtrToStringAuto(IntPtr) メソッド


アンマネージドのゼロ終端文字列から管理対象の [String](../../../system/string/) を作成します。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ptr | IntPtr | アンマネージド文字列へのポインタ。 |

### 戻り値

管理対象の文字列。

## Marshal::PtrToStringAuto(IntPtr, int) メソッド


アンマネージド文字列から管理対象の [String](../../../system/string/) を作成します。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr, int length)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ptr | IntPtr | アンマネージド文字列へのポインタ。 |
| length | int | アンマネージド文字列の長さ。 |

### 戻り値

管理対象の文字列。

## 関連項目

* クラス [String](../../../system/string/)
* クラス [Marshal](../)
* 名前空間 [System::Runtime::InteropServices](../../)
* ライブラリ [Aspose.Slides](../../../)