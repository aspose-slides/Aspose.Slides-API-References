---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides for C++ API リファレンス
description: UnmanagedMemoryStream の新しいインスタンスを作成します。
type: docs
weight: 118
url: /ja/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) コンストラクタ

[UnmanagedMemoryStream](../) の新しいインスタンスを作成します。

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pointer | **uint8_t** * | アンマネージド バッファへのポインタ |
| length | **int64_t** | バイト単位のアンマネージド バッファのサイズ |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) コンストラクタ

[UnmanagedMemoryStream](../) の新しいインスタンスを作成します。

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pointer | **uint8_t** * | アンマネージド バッファへのポインタ |
| length | **int64_t** | バイト単位のアンマネージド バッファのサイズ |
| capacity | **int64_t** | ストリームに割り当てられたメモリの総量 |
| access | [FileAccess](../../fileaccess/) | ストリームが読み取り専用、書き込み専用、またはその両方であるかを指定します |

## 参照

* 列挙型 [FileAccess](../../fileaccess/)
* クラス [UnmanagedMemoryStream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)