---
title: InsertClone()
second_title: Aspose.Slides C++ API 参考
description: 在集合的指定位置插入指定幻灯片的副本。
type: docs
weight: 27
url: /zh/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) method


在集合的指定位置插入指定幻灯片的副本。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 要克隆的 [Slide](../../slide/)。 |

### 返回值

已插入的幻灯片。

## 备注



在不同演示文稿之间克隆幻灯片时，幻灯片的母版也可能被克隆。内部注册表用于跟踪自动克隆的母版，以防止同一母版幻灯片被创建多个克隆。手动克隆母版幻灯片既不会被阻止也不会被注册。如果需要对克隆过程进行更精细的控制，可使用 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) 或 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) 来克隆幻灯片，使用 [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) 来克隆母版。 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method


在集合的指定位置插入指定幻灯片的副本。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 要克隆的 [Slide](../../slide/)。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 新幻灯片使用的布局幻灯片。 |

### 返回值

已插入的幻灯片。

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method


在集合的指定位置插入指定源幻灯片的副本。将自动从指定的母版中选择适当的布局（适当的布局是与源幻灯片布局具有相同 Type 或 Name 的布局）。如果在指定的母版中没有适当的布局，则会克隆源幻灯片的布局（当 allowCloneMissingLayout 为 true 时），否则将抛出 PptxEditException（当 allowCloneMissingLayout 为 false 时）。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 新幻灯片的索引。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 要克隆的 [Slide](../../slide/)。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新幻灯片使用的母版幻灯片。 |
| allowCloneMissingLayout | **bool** | 如果在指定的母版中没有适当的布局，则克隆源幻灯片的布局（当 allowCloneMissingLayout 为 true 时），否则抛出 PptxEditException（当 allowCloneMissingLayout 为 false 时）。 |

### 返回值

已插入的幻灯片。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlide](../../islide/)
* 类 [ISlideCollection](../)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [IMasterSlide](../../imasterslide/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)