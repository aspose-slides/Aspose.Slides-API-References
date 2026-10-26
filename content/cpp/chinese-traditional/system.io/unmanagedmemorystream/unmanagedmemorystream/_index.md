---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides for C++ API 參考
description: 建構 UnmanagedMemoryStream 的新實例。
type: docs
weight: 118
url: /zh-hant/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) 建構子

建構 [UnmanagedMemoryStream](../) 的新實例。

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pointer | **uint8_t** * | 指向非受管理緩衝區的指標 |
| length | **int64_t** | 非受管理緩衝區的大小（以位元組為單位） |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) 建構子

建構 [UnmanagedMemoryStream](../) 的新實例。

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pointer | **uint8_t** * | 指向非受管理緩衝區的指標 |
| length | **int64_t** | 非受管理緩衝區的大小（以位元組為單位） |
| capacity | **int64_t** | 指派給串流的總記憶體量 |
| access | [FileAccess](../../fileaccess/) | 指定串流應為唯讀、唯寫或兩者皆可 |

## 參見

* 列舉 [FileAccess](../../fileaccess/)
* 類別 [UnmanagedMemoryStream](../)
* 名稱空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)