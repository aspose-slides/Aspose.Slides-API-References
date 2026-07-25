---
title: PtrToStringUni()
second_title: Aspose.Slides for C++ API リファレンス
description: アンマネージドのゼロ終端 Unicode 文字列からマネージド String を作成します。
type: docs
weight: 300
url: /ja/system.runtime.interopservices/marshal/ptrtostringuni/
---
## Marshal::PtrToStringUni(IntPtr) メソッド


アンマネージドのゼロ終端 Unicode 文字列からマネージド [String](../../../system/string/) を作成します。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | IntPtr | アンマネージド文字列へのポインタ。 |

### 戻り値

マネージド文字列。

## Marshal::PtrToStringUni(IntPtr, int) メソッド


アンマネージド Unicode 文字列からマネージド [String](../../../system/string/) を作成します。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr, int length)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | IntPtr | アンマネージド文字列へのポインタ。 |
| length | int | アンマネージド文字列の長さ。 |

### 戻り値

マネージド文字列。

## 参照

* クラス [String](../../../system/string/)
* クラス [Marshal](../)
* 名前空間 [System::Runtime::InteropServices](../../)
* ライブラリ [Aspose.Slides](../../../)