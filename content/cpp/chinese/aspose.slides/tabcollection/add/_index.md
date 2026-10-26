---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 向集合中添加一个 Tab。
type: docs
weight: 53
url: /zh/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) 方法

将 [Tab](../../tab/) 添加到集合中。

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```

### 返回值

已添加的选项卡。

## TabCollection::Add(System::SharedPtr\<ITab\>) 方法

将 [Tab](../../tab/) 添加到集合中。

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | 要在集合末尾添加的 [Tab](../../tab/) 对象。 |

### 返回值

添加选项卡的索引。

## 另请参见

* 枚举 [TabAlignment](../../tabalignment/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ITab](../../itab/)
* 类 [TabCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)