---
title: IsStringLiteral
second_title: Aspose.Slides C++ API 参考
description: 用于检查类型是否为字符串字面量的模板技巧。
type: docs
weight: 1704
url: /zh/system/isstringliteral/
---
## IsStringLiteral 结构体


检查类型是否为字符串字面量的模板技巧。

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 检查的类型。 |
| CharT | 用于比较的字符类型。 |

## 另见

* Namespace [System](../)
* Library [Aspose.Slides](../../)