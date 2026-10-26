---
title: RunWorkerCompletedEventArgs()
second_title: Aspose.Slides for C++ API 参考
description: 构造函数。
type: docs
weight: 1
url: /zh/system.componentmodel/runworkercompletedeventargs/runworkercompletedeventargs/
---
## RunWorkerCompletedEventArgs::RunWorkerCompletedEventArgs(const System::SharedPtr\<System::Object\>\&, const System::Exception\&, bool) 构造函数

构造函数。

```cpp
System::ComponentModel::RunWorkerCompletedEventArgs::RunWorkerCompletedEventArgs(const System::SharedPtr<System::Object> &result, const System::Exception &error, bool canceled)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| result | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | 异步操作的结果。 |
| error | const [System::Exception](../../../system/exception/)\& | 异步操作期间发生的任何错误。 |
| canceled | **bool** | 指示异步操作是否已取消的值。 |

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [Exception](../../../system/exception/)
* 类 [Object](../../../system/object/)
* 类 [RunWorkerCompletedEventArgs](../)
* 命名空间 [System::ComponentModel](../../)
* 库 [Aspose.Slides](../../../)