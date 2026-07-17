---
title: AddClone()
second_title: Aspose.Slides C++ API 参考
description: 向演示文稿中添加指定布局幻灯片的副本。
type: docs
weight: 1
url: /zh/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 方法

将指定布局幻灯片的副本添加到演示文稿中。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 用于克隆。 |

### 返回值

已添加的幻灯片。

## 备注

在不同演示文稿之间克隆布局时，布局的母版也可以被克隆，以保留源格式。内部注册表用于跟踪自动克隆的母版，以防止创建同一母版幻灯片的多个克隆。手动克隆母版幻灯片既不会被阻止，也不会被记录。

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) 方法

将指定布局幻灯片的副本添加到演示文稿中。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 用于克隆。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 用于新布局的母版幻灯片。 |

### 返回值

已添加的幻灯片。

## 备注

1) 新布局将在目标演示文稿中链接到已定义的母版。因此这相当于在 PowerPoint 中使用 \"Use Destination Theme\" 选项进行复制/粘贴。2) 此方法的等价方法是 [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/)，通过 [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) 属性访问。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [GlobalLayoutSlideCollection](../)
* 类 [IMasterSlide](../../imasterslide/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)