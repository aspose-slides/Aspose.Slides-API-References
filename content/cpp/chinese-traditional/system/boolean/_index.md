---
title: Boolean
second_title: Aspose.Slides for C++ API 參考
description: 保存 System.Boolean .Net 類型的靜態成員的類別。
type: docs
weight: 79
url: /zh-hant/system/boolean/
---
## Boolean 類別

保存 [System.Boolean](./) .[Net](../../system.net/) 類型的靜態成員的類別。

```cpp
class Boolean
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | 將指定的字串轉換為 bool 類型的值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | 將指定的字串轉換為 bool 類型的值。 |

## 欄位

| 欄位 | 描述 |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) 為 'false' 布林值的表示。 |
| static [TrueString](./truestring/) | [String](../string/) 為 'true' 布林值的表示。 |

## 備註

```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // 建立布林變數。
  bool isWeekend = false;

  // 解析輸入字串並輸出結果。
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
此程式碼範例產生以下輸出：
是否週末：是
*/
```

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)