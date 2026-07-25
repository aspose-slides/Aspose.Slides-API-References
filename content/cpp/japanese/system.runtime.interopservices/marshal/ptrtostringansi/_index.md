---
title: PtrToStringAnsi()
second_title: Aspose.Slides for C++ API リファレンス
description: アンマネージドのヌル終端 UTF8 文字列からマネージド String を作成します。
type: docs
weight: 274
url: /ja/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) メソッド

アンマネージドのヌル終端 UTF8 文字列からマネージド [String](../../../system/string/) を作成します。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ptr | IntPtr | アンマネージド文字列へのポインター。 |

### 戻り値

マネージド文字列。

## Marshal::PtrToStringAnsi(IntPtr, int) メソッド

アンマネージド UTF8 文字列からマネージド [String](../../../system/string/) を作成します。

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ptr | IntPtr | アンマネージド文字列へのポインター。 |
| length | int | アンマネージド文字列の長さ。 |

### 戻り値

マネージド文字列。

## 参照

* クラス [String](../../../system/string/)
* クラス [Marshal](../)
* 名前空間 [System::Runtime::InteropServices](../../)
* ライブラリ [Aspose.Slides](../../../)