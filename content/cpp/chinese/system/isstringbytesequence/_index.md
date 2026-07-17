---
title: IsStringByteSequence
second_title: Aspose.Slides for C++ API 参考
description: 用于检查类型是否为字符串字符序列的模板技巧。
type: docs
weight: 1691
url: /zh/system/isstringbytesequence/
---
## IsStringByteSequence 结构体

模板技巧，用于检查类型是否是字符串字符序列。

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 检查的类型。 |
| CharT | 要检查的字符类型。 |

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)