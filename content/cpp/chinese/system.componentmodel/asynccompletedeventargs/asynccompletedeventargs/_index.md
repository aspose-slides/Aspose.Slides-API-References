---
title: AsyncCompletedEventArgs()
second_title: Aspose.Slides C++ API 参考
description: 构造函数.
type: docs
weight: 1
url: /zh/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() 构造函数

构造函数。

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) 构造函数

初始化 [System.ComponentModel.AsyncCompletedEventArgs](../) 类的新实例。

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | 在异步操作期间发生的任何错误。 |
| canceled | **bool** | 指示异步操作是否已取消的值。 |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 传递给 [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) 方法的可选用户提供的状态对象。 |

## 另见

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [AsyncCompletedEventArgs](../)
* 类 [Object](../../../system/object/)
* 命名空间 [System::ComponentModel](../../)
* 库 [Aspose.Slides](../../../)