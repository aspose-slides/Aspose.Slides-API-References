---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 向集合中添加 Tab。
type: docs
weight: 14
url: /zh/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) 方法

Adds a [Tab](../../tab/) to the collection.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) position. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) 对齐。 |

### 返回值

已添加的制表位。

## ITabCollection::Add(System::SharedPtr\<ITab\>) 方法

Adds a [Tab](../../tab/) to the collection.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | 要在集合末尾添加的 [Tab](../../tab/) 对象。 |

### 返回值

添加制表位的索引。

## 另请参见

* 枚举 [TabAlignment](../../tabalignment/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ITab](../../itab/)
* 类 [ITabCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)