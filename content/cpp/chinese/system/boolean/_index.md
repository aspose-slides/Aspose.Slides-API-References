---
title: Boolean
second_title: Aspose.Slides for C++ API 参考
description: 保持 System.Boolean .Net 类型的静态成员的类。
type: docs
weight: 79
url: /zh/system/boolean/
---
## 布尔类

保持 [System.Boolean](./) .[Net](../../system.net/) 类型的静态成员的类。

```cpp
class Boolean
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | 将指定的字符串转换为 bool 类型的值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | 将指定的字符串转换为 bool 类型的值。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) 表示 'false' 布尔值。 |
| static [TrueString](./truestring/) | [String](../string/) 表示 'true' 布尔值。 |

## 备注



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // 创建布尔变量。
  bool isWeekend = false;

  // 解析输入字符串并打印结果。
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
此代码示例产生以下输出：
Is weekend: Yes
*/
```

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)