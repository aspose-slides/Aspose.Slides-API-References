---
title: WeakReference<>
second_title: Aspose.Slides for C++ API 参考
description: 表示一个弱引用，该引用在仍然允许对象被删除的同时引用该对象。
type: docs
weight: 1496
url: /zh/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> 类


表示一个弱引用，该引用在仍然允许对象被删除的同时引用该对象。

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | 获取一个指示，表明当前 WeakReference 对象引用的对象是否已被删除。 |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | 获取当前 WeakReference 对象引用的对象（目标）。 |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 设置当前 WeakReference 对象引用的对象（目标）。 |
|  [WeakReference](./weakreference/)() | 默认构造函数。 |
|  [WeakReference](./weakreference/)(std::nullptr_t) | 从 nullptr 的构造函数。 |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 初始化 WeakReference 类的新实例，引用指定的对象。 |
|  [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | 初始化 WeakReference 类的新实例，引用指定的对象。 |
## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)