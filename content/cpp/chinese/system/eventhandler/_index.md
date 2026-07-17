---
title: EventHandler
second_title: Aspose.Slides for C++ API 参考
description: "表示一个对事件作出反应并处理该事件的方法。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 3667
url: /zh/system/eventhandler/
---
## EventHandler 类型定义

表示一个对事件作出反应并处理该事件的方法。此类型应在栈上分配，并通过值或引用传递给函数。绝不可使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)