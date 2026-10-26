---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新实例。
type: docs
weight: 14
url: /zh/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) 构造函数


构造一个新实例。

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | 在异步操作期间出现的任何错误。 |
| cancelled | **bool** | 指示异步操作是否已取消的值。 |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 传递给 [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) 方法的可选用户提供的状态对象。 |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 异步操作结果的集合。 |

## 另请参见

* 类型定义 [Exception](../../../system/exception/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Object](../../../system/object/)
* 类 [InvokeCompletedEventArgs](../)
* 命名空间 [System::Web::Services::Protocols](../../)
* 库 [Aspose.Slides](../../../)