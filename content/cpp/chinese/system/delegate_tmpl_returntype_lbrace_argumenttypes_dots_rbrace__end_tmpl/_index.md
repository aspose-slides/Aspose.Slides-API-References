---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API 参考
description: "表示指向函数、方法或函数对象的指针。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 287
url: /zh/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> 类

表示指向函数、方法或函数对象的指针。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| ReturnType | 函数、方法或函数对象指针的返回类型，由该 class 表示 |
| ArgumentTypes | 函数、方法或函数对象指针的参数列表，由该 class 表示 |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [Delegate](./delegate/)() | 默认构造函数。构造不指向任何内容的委托对象。 |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | 移动复制构造函数。获取指定委托所指向实体的所有权。 |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | 构造函数。从指定的自由函数或静态方法指针构造委托对象。 |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | 构造函数。从 std::bind() 生成的函数对象指针构造委托。 |
|  [Delegate](./delegate/)(int, T\&) | 构造函数。从指定的函数对象构造委托。 |
|  [Delegate](./delegate/)(long, T\&&) | 移动构造函数。从指定的函数对象构造委托。 |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | 构造函数。构造指向指定对象的指定非静态方法的委托。 |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 构造函数。构造指向指定对象的指定非静态方法的委托。 |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | 构造指向 std::function 函数对象的委托对象。 |
| **bool** [Empty](./empty/)() const | 确定当前委托对象是否为空，例如不指向任何实体。 |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | 调用当前委托对象指向的函数、方法或函数对象。 |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | 移动赋值运算符。获取指定委托所指向实体的所有权。 |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | 比较两个委托对象以检查它们是否指向相同实体。 |

## 备注

```cpp
#include "system/delegate.h"
#include <iostream"

// 声明委托。
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // 将 PrintMessage 函数的地址赋给变量。
  Message mes = Message(&PrintMessage);

  // 调用函数。
  mes();

  return 0;
}
/*
此代码示例产生以下输出：
你好，世界！
*/
```

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)