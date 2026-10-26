---  
title: IsInstanceOfType()  
second_title: Aspose.Slides for C++ API 参考  
description: 确定指定的对象是否是当前类型的实例。  
type: docs  
weight: 131  
url: /zh/system/typeinfo/isinstanceoftype/  
---
## TypeInfo::IsInstanceOfType(const SharedPtr\<Object\>\&) const 方法

确定指定的对象是否是当前类型的实例。

```cpp
bool System::TypeInfo::IsInstanceOfType(const SharedPtr<Object> &obj) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 要与当前类型进行比较的对象 |

### 返回值

如果当前类型在 obj 表示的对象的继承层次结构中，则为 true

## 参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Object](../../object/)
* 类 [TypeInfo](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)