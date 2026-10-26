---
title: Comparison
second_title: Aspose.Slides for C++ API 參考
description: "表示指向比較相同類型之兩個物件的方法的指標。此類型應分配於堆疊上，並以值或參考傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 183
url: /zh-hant/system/comparison/
---
## 比較類別


表示指向比較相同類型之兩個物件的方法的指標。此類型應分配於堆疊上，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 方法比較的物件類型 |
## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | 呼叫目前物件指向的可呼叫物件。 |
## 備註



```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// 代表動態陣列的模板類別。
template <typename T>
class MyArray
{
  // 用於儲存陣列資料。
  std::vector<T> m_data;

public:
  // 建構我們動態陣列的新實例。
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // 用於排序陣列資料。此方法接受一個
  // 'System::Comparison' 模板類別。
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // 回傳我們動態陣列儲存的元素數量。
  size_t get_Size()
  {
    return m_data.size();
  }

  // 用於取得指定索引處的元素。
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // 建立 MyArray 類別的實例，並指定元素。
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // 依升序排列動態陣列的元素。
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // 列印動態陣列的元素。
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
此程式碼範例產生以下輸出：
a
b
c
d
e
*/
```

## 另請參閱

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)