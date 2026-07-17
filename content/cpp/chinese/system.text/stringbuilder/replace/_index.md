---
title: Replace()
second_title: Aspose.Slides C++ API 参考
description: 通过构建器替换子字符串。
type: docs
weight: 196
url: /zh/system.text/stringbuilder/replace/
---
## StringBuilder::Replace(const String\&, const String\&) 方法

通过构建器替换子字符串。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于替换。 |
| newString | const [String](../../../system/string/)\& | 替换字符串。 |

### 返回值

此指针。

## StringBuilder::Replace(const String\&, const String\&, int, int) 方法

通过构建器的范围替换子字符串。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString, int position, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) 用于替换。 |
| newString | const [String](../../../system/string/)\& | 替换字符串。 |
| position | int | 构建器的替换范围起始位置。 |
| count | int | 构建器的替换范围长度。 |

### 返回值

此指针。

## StringBuilder::Replace(char_t, char_t) 方法

通过构建器替换字符。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldChar | char_t | 要替换的字符。 |
| newChar | char_t | 替换字符。 |

### 返回值

此指针。

## StringBuilder::Replace(char_t, char_t, int, int) 方法

通过构建器的范围替换字符。

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar, int startIndex, int count)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldChar | char_t | 要替换的字符。 |
| newChar | char_t | 替换字符。 |
| startIndex | int | 构建器的替换范围起始位置。 |
| count | int | 构建器的替换范围长度。 |

### 返回值

此指针。

## 另见

* 类 [StringBuilder](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Text](../../)
* Library [Aspose.Slides](../../../)