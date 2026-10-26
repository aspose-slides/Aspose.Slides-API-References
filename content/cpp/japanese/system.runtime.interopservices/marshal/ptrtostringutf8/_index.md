---
title: PtrToStringUTF8()
second_title: Aspose.Slides for C++ API リファレンス
description: アンマネージドのゼロ終端 UTF8 文字列から、マネージド String を作成します。
type: docs
weight: 313
url: /ja/system.runtime.interopservices/marshal/ptrtostringutf8/
---
## Marshal::PtrToStringUTF8(IntPtr) method

アンマネージドのゼロ終端 UTF8 文字列から、マネージド [String](../../../system/string/) を作成します。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | IntPtr | アンマネージド文字列へのポインタ。 |

### 戻り値

マネージド文字列です。

## Marshal::PtrToStringUTF8(IntPtr, int) method

アンマネージド UTF8 文字列から、マネージド [String](../../../system/string/) を作成します。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr, int length)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | IntPtr | アンマネージド文字列へのポインタ。 |
| length | int | アンマネージド文字列の長さ。 |

### 戻り値

マネージド文字列です。

## 参照

* クラス [String](../../../system/string/)
* クラス [Marshal](../)
* 名前空間 [System::Runtime::InteropServices](../../)
* ライブラリ [Aspose.Slides](../../../)