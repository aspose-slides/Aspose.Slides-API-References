---
title: ExceptionWrapper
second_title: Aspose.Slides for C++ API 参考
description: 表示从 Exception 类派生的异常的包装器的模板。
type: docs
weight: 833
url: /zh/system/exceptionwrapper/
---
## ExceptionWrapper 类


表示从 Exception 类派生的异常的包装器的模板。

```cpp
template<typename T>class ExceptionWrapper
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | 构造一个不表示任何异常的 [ExceptionWrapper](./) 类的空实例。 |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | 构造一个包含传入指针的 [ExceptionWrapper](./) 类实例。 |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | 拷贝构造函数。 |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | 移动构造函数。 |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | 构造函数，将参数转发给 Exception 类的构造函数，并创建持有新 Exception 类实例的智能指针。 |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | 隐式转换运算符，转换为 SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | 允许访问 Exception 对象的成员。 |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | 赋值运算符。 |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | 移动赋值运算符。 |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | 获取 Exception 类型的 [System::TypeInfo](../typeinfo/) 对象的快捷方式。 |
## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [ExceptionType](./exceptiontype/) | 用于转换函数。 |
## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)