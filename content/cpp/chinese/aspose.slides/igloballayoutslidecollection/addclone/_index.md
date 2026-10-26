---
title: AddClone()
second_title: Aspose.Slides C++ API 参考
description: 向演示文稿中添加指定布局幻灯片的副本。
type: docs
weight: 1
url: /zh/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Adds a copy of a specified layout slide to the presentation.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 用于克隆。 |

### 返回值

Added slide.
## 备注



在不同演示文稿之间克隆布局时，布局的母版也可以被克隆，以保持源格式。内部注册表用于跟踪自动克隆的母版，防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止，也不会被登记。 
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method


Adds a copy of a specified layout slide to the presentation.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 用于克隆。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新布局的母版幻灯片。 |

### 返回值

Added slide.
## 备注



新布局将在目标演示文稿中与指定的母版关联。因此，这相当于在 PowerPoint 中使用 "Use Destination Theme" 选项进行复制/粘贴。 
## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IGlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)