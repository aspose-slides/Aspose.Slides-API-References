---
title: get_SlideSize()
second_title: Aspose.Slides for C++ API 参考
description: 返回幻灯片大小对象。只读 ISlideSize.
type: docs
weight: 79
url: /zh/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() 方法


返回幻灯片大小对象。只读 [ISlideSize](../../islidesize/)。

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## 备注


以下示例展示如何在 PowerPoint [Presentation](../) 中更改幻灯片大小。 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
以下示例展示如何为 PowerPoint [Presentation](../) 设置相对于内容缩放的幻灯片大小。 
```cpp
// 实例化一个表示演示文稿文件的 Presentation 对象
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// 将生成的演示文稿的幻灯片尺寸设置为源文稿的尺寸
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// SetSize 方法用于在缩放内容以确保适配的情况下设置幻灯片尺寸
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// SetSize 方法用于在最大化内容尺寸的情况下设置幻灯片尺寸
// 将演示文稿保存到磁盘
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
以下示例展示如何在 PowerPoint [Presentation](../) 中指定自定义幻灯片大小。 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4 纸张尺寸
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISlideSize](../../islidesize/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)