---
title: AddClone()
second_title: Aspose.Slides C++ API 参考
description: 向集合末尾添加指定布局幻灯片的副本。
type: docs
weight: 1
url: /zh/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 方法

在集合的末尾添加指定布局幻灯片的副本。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 要克隆。 |

### 返回值

已添加的幻灯片。

## 备注

1) 新布局将与此布局幻灯片集合的父母版幻灯片关联。因此，这相当于在 PowerPoint 中使用 \"Use Destination Theme\" 选项的复制/粘贴。2) 此方法的对应方法是通过 [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) 属性访问的 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) 方法。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [IMasterLayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)