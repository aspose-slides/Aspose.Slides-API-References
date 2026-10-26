---
title: what()
second_title: Aspose.Slides for C++ API 参考
description: "实现 what() 方法，该方法由 ExceptionWrapper 类调用。尽管此类未从 std::exception 继承，但派生类可以使用受保护/私有成员来实现它们的逻辑。将此方法实现移动到 ExceptionWrapper 可能会破坏该逻辑。"
type: docs
weight: 105
url: /zh/system/details_exception/what/
---
## Details_Exception::what() const 方法

实现 [what()](./) 方法，该方法由 [ExceptionWrapper](../../exceptionwrapper/) 类调用。尽管此类未从 std::exception 继承，但派生类可以使用受保护/私有成员来实现它们的逻辑。将此方法实现移到 [ExceptionWrapper](../../exceptionwrapper/) 可能会破坏该逻辑。

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### 返回值

异常的描述。

## 另请参见

* 类 [Details_Exception](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)