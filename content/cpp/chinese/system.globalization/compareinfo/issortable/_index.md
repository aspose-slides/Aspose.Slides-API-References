---
title: IsSortable()
second_title: Aspose.Slides C++ API 参考
description: 检查指定字符是否可排序。
type: docs
weight: 196
url: /zh/system.globalization/compareinfo/issortable/
---
## CompareInfo::IsSortable(char16_t) 方法


检查指定字符是否可排序。

```cpp
static bool System::Globalization::CompareInfo::IsSortable(char16_t ch)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ch | char16_t | Unicode 字符。 |

### 返回值

如果 **ch** 可排序，则返回 True；否则返回 false。

## CompareInfo::IsSortable(const String\&) 方法


检查指定字符串是否可排序。

```cpp
static bool System::Globalization::CompareInfo::IsSortable(const String &text)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 一个字符串。 |

### 返回值

如果 **text** 不为空且 **text** 中的所有字符均可排序，则返回 True；否则返回 false。

## 另请参阅

* 类 [CompareInfo](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)