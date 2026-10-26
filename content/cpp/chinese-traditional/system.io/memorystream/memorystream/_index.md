---
title: MemoryStream()
second_title: Aspose.Slides for C++ API 參考
description: 建立 MemoryStream 類別的新執行個體，初始容量為 0。
type: docs
weight: 1
url: /zh-hant/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() 建構函式

建立 [MemoryStream](../) 類別的新執行個體，初始容量為 0。

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) 建構函式

建立 [MemoryStream](../) 類別的新執行個體，該類別表示基於指定大小之記憶體緩衝區的串流。

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| capacity_ | int | 與所建立物件所表示之串流相關聯的記憶體緩衝區的位元組大小 |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) 建構函式

建立 [MemoryStream](../) 類別的新執行個體，該類別表示連接至指定記憶體緩衝區的記憶體串流。參數用於指定串流是否可寫入。

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 用作記憶體緩衝區的位元組陣列，所建立之物件所表示的串流將基於此緩衝區 |
| writable | **bool** | 指定串流是否應為可寫入 |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) 建構函式

建立 [MemoryStream](../) 類別的新執行個體，該類別表示連接至指定記憶體緩衝區之片段的記憶體串流；片段起始於指定索引且包含指定數量的元素。參數用於指定串流是否可寫入以及是否可呼叫方法 GetBytes()。

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 位元組陣列，其片段將被用作記憶體緩衝區，所建立之物件所表示的串流將基於此緩衝區 |
| index | int | **content** 中片段開始之元素的 0 基索引 |
| count | int | 片段中包含的 **content** 元素數量 |
| writable | **bool** | 指定串流是否應為可寫入 |
| publiclyVisible | **bool** | 指定底層記憶體緩衝區是否應提供給呼叫方法 GetByte() 的呼叫端 |

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [MemoryStream](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)