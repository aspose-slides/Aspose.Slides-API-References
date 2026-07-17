---
title: IOControl()
second_title: Aspose.Slides C++ API 参考
description: 为套接字设置低级操作模式。
type: docs
weight: 703
url: /zh/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

为套接字设置低级操作模式。

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ioControlCode | **int32_t** | 要执行的操作的控制代码。 |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含输入数据的字节数组。 |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含输出数据的字节数组。 |

### 返回值

**optionOutValue** 参数中的字节数。

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 方法

为套接字设置低级操作模式。

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | 要执行的操作的控制代码。 |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含输入数据的字节数组。 |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 包含输出数据的字节数组。 |

### 返回值

**optionOutValue** 参数中的字节数。

## 另请参见

* 枚举 [IOControlCode](../../iocontrolcode/)
* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类 [Socket](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)