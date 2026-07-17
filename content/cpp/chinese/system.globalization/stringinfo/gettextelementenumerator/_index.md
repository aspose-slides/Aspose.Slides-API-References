---
title: GetTextElementEnumerator()
second_title: Aspose.Slides C++ API 参考
description: 创建枚举器以遍历字符串的字符。
type: docs
weight: 118
url: /zh/system.globalization/stringinfo/gettextelementenumerator/
---
## StringInfo::GetTextElementEnumerator(const String\&) 方法

创建枚举器以遍历字符串的字符。

```cpp
static SharedPtr<TextElementEnumerator> System::Globalization::StringInfo::GetTextElementEnumerator(const String &str)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于遍历。 |

### 返回值

新创建的枚举器。

## StringInfo::GetTextElementEnumerator(const String\&, int) 方法

创建枚举器以从指定索引开始遍历字符串的字符。

```cpp
static SharedPtr<TextElementEnumerator> System::Globalization::StringInfo::GetTextElementEnumerator(const String &str, int index)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于遍历。 |
| index | int | 起始索引。 |

### 返回值

新创建的枚举器。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [TextElementEnumerator](../../textelementenumerator/)
* 类 [String](../../../system/string/)
* 类 [StringInfo](../)
* 命名空间 [System::Globalization](../../)
* 库 [Aspose.Slides](../../../)