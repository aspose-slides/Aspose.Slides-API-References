---
title: BufferedStream()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個 BufferedStream 物件，將指定的串流包裝起來，並使用 4096 位元組長的緩衝區。
type: docs
weight: 1
url: /zh-hant/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) 建構子

建構一個 [BufferedStream](../) 物件，將指定的串流包裝起來，並使用 4096 位元組長的緩衝區。

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 底層的 [Stream](../../stream/) 物件 |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) 建構子

建構一個 [BufferedStream](../) 物件，將指定的串流包裝起來，並使用指定大小的緩衝區。

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 底層的 [Stream](../../stream/) 物件 |
| bufferSize | int | 緩衝區的大小（位元組） |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Stream](../../stream/)
* 類別 [BufferedStream](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)