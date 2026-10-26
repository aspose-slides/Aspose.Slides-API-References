---
title: ToUpper()
second_title: Aspose.Slides for C++ API 参考
description: 将指定字符转换为大写。
type: docs
weight: 222
url: /zh/system/char/toupper/
---
## Char::ToUpper(char_t) 方法

将指定字符转换为大写。

```cpp
static char_t System::Char::ToUpper(char_t c)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 待转换的字符 |

### 返回值

如果指定字符是小写字母，则返回该字符的大写形式；否则返回原字符

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) 方法

将指定字符转换为大写。

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| c | char_t | 待转换的字符 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 提供特定文化的大小写规则的对象。 |

### 返回值

如果指定字符是小写字母，则返回该字符的大写形式；否则返回原字符

## 另请参见

* Typedef [SharedPtr](../../sharedptr/)
* Class [Char](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)