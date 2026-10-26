---
title: EndRead()
second_title: Aspose.Slides C++ API 参考
description: 等待指定的异步读取操作完成。
type: docs
weight: 183
url: /zh/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) 方法

等待指定的异步读取操作完成。

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | 表示异步读取操作的[IAsyncResult](../../../system/iasyncresult/)对象 |

### 返回值

在由 **asyncResult** 表示的读取操作期间读取的字节数

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [Stream](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)