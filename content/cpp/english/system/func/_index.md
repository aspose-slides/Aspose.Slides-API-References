---
title: Func
second_title: Aspose.Slides for C++ API Reference
description: "Function delegate. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 833
url: /system/func/
---
## Func class


Function delegate. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Args | Call arguments, then mandatory return type. |
## Methods

| Method | Description |
| --- | --- |
|  [Func](./func/)() | Default constructor that creates null-Func. |
|  [Func](./func/)(T\&&) | Constructor that constructs [Func](./) object and assigns value (either actual callback or nullptr) to it. |
|  [Func](./func/)(const [Func](./)\&) | Copy constructor. |
|  [Func](./func/)([Func](./)\&&) | Move constructor. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Copy assignment. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Move assignment. |
|  [~Func](./~func/)() | Destructor. |
## Remarks



```cpp
#include "system/func.h"
#include <iostream>

// This function accepts an instance of the System::Func delegate as a parameter.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Create an instance of the System::Func delegate.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Pass the created instance as a function argument.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
This code example produces the following output:
1
4
9
*/
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)