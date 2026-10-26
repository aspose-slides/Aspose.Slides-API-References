---
title: FromAscii()
second_title: Aspose.Slides for C++ API 参考
description: 从 ASCII 字符串创建 String。
type: docs
weight: 950
url: /zh/system/string/fromascii/
---
## String::FromAscii(const char *) 方法

从 ASCII 字符串创建 [String](../)。

```cpp
static String System::String::FromAscii(const char *asciiStr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asciiStr | const char * | 指向使用 ASCII 代码页编码的以空字符结尾的字符串的指针。 |

### 返回值

[String](../) 表示传入字符串的对象。

## String::FromAscii(const char *, int) 方法

从 ASCII 字符串创建 [String](../)。

```cpp
static String System::String::FromAscii(const char *asciiStr, int len)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asciiStr | const char * | 指向使用 ASCII 代码页编码的字符串的指针。 |
| len | int | 要处理的字符数。 |

### 返回值

[String](../) 表示传入字符串的对象。

## String::FromAscii(const std::string\&) 方法

从 ASCII 字符串创建 [String](../)。

```cpp
static String System::String::FromAscii(const std::string &asciiStr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asciiStr | const std::string\& | ASCII 编码的字符串。 |

### 返回值

[String](../) 表示传入字符串的对象。

## 参见

* 类 [String](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)