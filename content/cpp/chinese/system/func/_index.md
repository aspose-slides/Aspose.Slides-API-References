---
title: Func
second_title: Aspose.Slides for C++ API 参考
description: "函数委托。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 859
url: /zh/system/func/
---
## Func 类

函数委托。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Args | 调用参数，然后是必需的返回类型。 |

## 方法

| 方法 | 描述 |
| --- | --- |
|  [Func](./func/)() | 创建空 Func 的默认构造函数。 |
|  [Func](./func/)(T\&&) | 构造 [Func](./) 对象并为其分配值（实际回调或 nullptr）。 |
|  [Func](./func/)(const [Func](./)\&) | 拷贝构造函数。 |
|  [Func](./func/)([Func](./)\&&) | 移动构造函数。 |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | 拷贝赋值。 |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | 移动赋值。 |
|  [~Func](./~func/)() | 析构函数。 |

## 备注



```cpp
#include "system/func.h"
#include <iostream>

// 此函数接受一个 System::Func 委托实例作为参数。
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // 创建一个 System::Func 委托实例。
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // 将创建的实例作为函数参数传递。
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
此代码示例产生以下输出：
1
4
9
*/
```

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)