---
title: EndRead()
second_title: Aspose.Slides for C++ API 参考
description: 等待指定的异步读取操作完成。
type: docs
weight: 430
url: /zh/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) 方法

等待指定的异步读取操作完成。

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 一个 [IAsyncResult](../../../system/iasyncresult/) 对象，表示异步读取操作 |

### 返回值

在由 **asyncResult** 表示的读取操作期间读取的字节数

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [SslStream](../)
* 命名空间 [System::Net::Security](../../)
* 库 [Aspose.Slides](../../../)