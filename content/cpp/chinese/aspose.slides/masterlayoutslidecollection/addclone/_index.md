---
title: AddClone()
second_title: Aspose.Slides C++ API 参考
description: 向集合的末尾添加指定布局幻灯片的副本。
type: docs
weight: 1
url: /zh/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 方法

向集合的末尾添加指定布局幻灯片的副本。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 进行克隆。 |

## 返回值

已添加的幻灯片。

## 备注

1) 新布局将与该布局幻灯片集合的父母主幻灯片关联。因此这相当于在 PowerPoint 中使用 \"Use Destination Theme\" 选项的复制/粘贴。2) 此方法的类似方法是 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) 方法，可通过 [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) 属性访问。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ILayoutSlide](../../ilayoutslide/)
* 类 [MasterLayoutSlideCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)