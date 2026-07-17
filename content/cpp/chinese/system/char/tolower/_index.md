---
title: ToLower()
second_title: Aspose.Slides C++ API 参考
description: 将指定字符转换为小写。
type: docs
weight: 235
url: /zh/system/char/tolower/
---
## Char::ToLower(char_t) 方法

将指定字符转换为小写。

```cpp
static char_t System::Char::ToLower(char_t c)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要转换的字符 |

### 返回值

如果指定字符是大写字母，则返回其小写形式；否则返回原字符

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

将指定字符转换为小写。

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 要转换的字符 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 提供特定文化区分大小写规则的对象。 |

### 返回值

如果指定字符是大写字母，则返回其小写形式；否则返回原字符

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Char](../)
* 类 [CultureInfo](../../../system.globalization/cultureinfo/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)