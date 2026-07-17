---
title: SetValue()
second_title: Aspose.Slides for C++ API 参考
description: 将属性值设置为特定对象。
type: docs
weight: 14
url: /zh/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) 方法

将属性值设置为特定对象。

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 用于写入属性。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 要设置的属性值。 |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) 方法

将属性值设置为特定对象。

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 用于写入属性。 |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 这些是索引属性的可选索引值。对于非索引属性，此值应为 null。 |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | 要设置的属性值。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Object](../../../system/object/)
* 类 [PropertyInfo](../)
* 命名空间 [System::Reflection](../../)
* 库 [Aspose.Slides](../../../)