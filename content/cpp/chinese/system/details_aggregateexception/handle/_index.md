---
title: Handle()
second_title: Aspose.Slides for C++ API 参考
description: 对每个内部异常调用处理函数，并重新抛出任何未处理的异常。
type: docs
weight: 66
url: /zh/system/details_aggregateexception/handle/
---
## 详情_AggregateException::Handle(const Func\<Exception, bool\>\&) method

对每个内部异常调用处理函数，并重新抛出任何未处理的异常。

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | 一个接受 Exception 并在处理后返回 true 的函数。 |
## 备注

如果所有异常都已处理，则方法正常返回；否则，将抛出一个包含未处理异常的新 AggregateException。

## 另见

* 类型定义 [Exception](../../exception/)
* 类 [Func](../../func/)
* 类 [Details_AggregateException](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)