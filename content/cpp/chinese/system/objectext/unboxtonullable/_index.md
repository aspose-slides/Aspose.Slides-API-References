---
title: UnboxToNullable()
second_title: Aspose.Slides for C++ API 参考
description: 将对象解箱为可空类型。
type: docs
weight: 79
url: /zh/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) 方法


将对象解箱为可空类型。

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 用于解箱。 |
| safe | **bool** | 如果为 true，则在失败时返回 nullptr，否则抛出 InvalidCastException。 |

### 返回值

已解箱的可空值（可能为 null）。

## 另见

* 类 [Nullable](../../nullable/)
* 类 [SmartPtr](../../smartptr/)
* 类 [Object](../../object/)
* 类 [ObjectExt](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)