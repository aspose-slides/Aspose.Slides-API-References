---
title: GetValue()
second_title: Aspose.Slides for C++ API 参考
description: 从特定对象获取属性值。
type: docs
weight: 1
url: /zh/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) 方法


从特定对象获取属性值。

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 用于读取属性。 |

### 返回值

指定对象的指定属性的值。

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) 方法


从特定对象获取属性值。

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) 用于读取属性。 |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | 这些是索引属性的可选索引值。对于非索引属性，此值应为 null。 |

### 返回值

指定对象的指定属性的值。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 类 [Object](../../../system/object/)
* 类 [PropertyInfo](../)
* 命名空间 [System::Reflection](../../)
* 库 [Aspose.Slides](../../../)