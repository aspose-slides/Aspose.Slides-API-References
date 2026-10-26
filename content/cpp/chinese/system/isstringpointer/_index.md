---
title: IsStringPointer
second_title: Aspose.Slides C++ API 参考
description: 模板技巧，用于检查类型是否为指向字符字符串的指针。
type: docs
weight: 1717
url: /zh/system/isstringpointer/
---
## IsStringPointer struct

模板技巧，用于检查类型是否为指向字符字符串的指针。

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 已检查的类型。 |
| CharT | 要检查的字符类型。 |

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)