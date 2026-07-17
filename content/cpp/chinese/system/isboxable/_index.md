---
title: IsBoxable
second_title: Aspose.Slides for C++ API 参考
description: 模板谓词，用于检查是否支持对指定类型的装箱。
type: docs
weight: 1639
url: /zh/system/isboxable/
---
## IsBoxable struct


模板谓词，用于检查是否支持对指定类型的装箱。

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要检查的类型 |

## 参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)