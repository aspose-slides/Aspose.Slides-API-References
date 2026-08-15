---
title: Func
second_title: Aspose.Slides for C++ API 參考文件
description: "函式委派。此類型應在堆疊上分配，並以值或參考方式傳遞給函式。絕不要使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 859
url: /zh-hant/system/func/
---
## Func 類別


函式委派。此類型應在堆疊上分配，並以值或引用方式傳遞給函式。絕不要使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| Args | 呼叫參數，接著是必要的返回型別。 |
## 方法

| 方法 | 描述 |
| --- | --- |
|  [Func](./func/)() | 預設建構函式，會建立 null-Func。 |
|  [Func](./func/)(T\&&) | 建構函式，用於建構 [Func](./) 物件並將值（實際回呼或 nullptr）指派給它。 |
|  [Func](./func/)(const [Func](./)\&) | 複製建構函式。 |
|  [Func](./func/)([Func](./)\&&) | 移動建構函式。 |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | 複製指派。 |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | 移動指派。 |
|  [~Func](./~func/)() | 解構函式。 |
## 備註



```cpp
#include "system/func.h"
#include <iostream"

// 此函式接受 System::Func 委派的實例作為參數。
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // 建立 System::Func 委派的實例。
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // 將建立的實例作為函式引數傳遞。
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
此程式碼範例產生以下輸出：
1
4
9
*/
```

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)