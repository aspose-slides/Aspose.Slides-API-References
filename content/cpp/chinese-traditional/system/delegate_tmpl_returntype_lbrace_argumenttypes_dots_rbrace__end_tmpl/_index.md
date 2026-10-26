---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides for C++ API 參考文件
description: "表示指向函式、方法或函式物件的指標。此類型應在堆疊上分配，並以值或參考方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 287
url: /zh-hant/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> 類別


表示指向函式、方法或函式物件的指標。此類型應該在堆疊上分配，並以值或參考傳遞給函式。絕不要使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| ReturnType | 函式、方法或函式物件指標的返回型別，由此類別所代表 |
| ArgumentTypes | 函式、方法或函式物件指標的參數清單，由此類別所代表 |


## 方法

| 方法 | 描述 |
| --- | --- |
|  [Delegate](./delegate/)() | 預設建構子。建立不指向任何實體的 delegate 物件。 |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | 移動複製建構子。取得指定 delegate 所指向的實體的所有權。 |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | 建構子。從指定的自由函式或靜態方法指標建立 delegate 物件。 |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | 建構子。從 std::bind() 產生之函式物件的指定指標建立 delegate。 |
|  [Delegate](./delegate/)(int, T\&) | 建構子。從指定的函式物件建立 delegate。 |
|  [Delegate](./delegate/)(long, T\&&) | 移動建構子。從指定的函式物件建立 delegate。 |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | 建構子。建立指向指定物件之指定非靜態方法的 delegate。 |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | 建構子。建立指向指定物件之指定非靜態方法的 delegate。 |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | 建立指向 std::function 函式物件的 delegate 物件。 |
| **bool** [Empty](./empty/)() const | 判斷目前的 delegate 物件是否為空，例如不指向任何實體。 |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | 呼叫目前 delegate 物件所指向的函式、方法或函式物件。 |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | 移動指定運算子。取得指定 delegate 所指向的實體的所有權。 |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | 比較兩個 delegate 物件是否指向相同的實體。 |


## 備註



```cpp
#include "system/delegate.h"
#include <iostream"

// 宣告委託.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // 將 PrintMessage 函式的位址指派給變數.
  Message mes = Message(&PrintMessage);

  // 呼叫函式.
  mes();

  return 0;
}
/*
此程式範例會產生以下輸出:
Hello, world!
*/
```

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)