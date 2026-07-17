---
title: get_Slides()
second_title: Aspose.Slides for C++ API 参考
description: 返回演示文稿中定义的所有幻灯片的列表。只读 ISlideCollection.
type: docs
weight: 53
url: /zh/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() 方法

返回演示文稿中定义的所有幻灯片的列表。只读 [ISlideCollection](../../islidecollection/)。

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## 备注

以下示例展示了如何设置 PowerPoint 幻灯片的背景颜色 [Presentation](../)。 
```cpp
// 实例化表示演示文稿文件的 Presentation 类
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// 将第一个 ISlide 的背景颜色设置为蓝色
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
以下示例展示了如何设置 PowerPoint 幻灯片的背景图像 [Presentation](../)。 
```cpp
// 实例化表示演示文稿文件的 Presentation 类
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// 使用图像设置背景
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// 设置图片
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// 将图像添加到演示文稿的图像集合中
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// 将演示文稿写入磁盘
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
以下示例展示了如何添加幻灯片切换效果 [Presentation](../)。 
```cpp
// 实例化 Presentation 类以加载源演示文稿文件
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// 在第 1 张幻灯片上应用圆形切换效果
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// 在第 2 张幻灯片上应用梳形切换效果
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// 将演示文稿写入磁盘
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
以下示例展示了如何添加高级幻灯片 Transition。 
```cpp
// 实例化表示演示文稿文件的 Presentation 类
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// 在第 1 张幻灯片上应用圆形切换效果
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// 设置 3 秒的切换时间
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// 在第 2 张幻灯片上应用梳形切换效果
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// 设置 5 秒的切换时间
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// 在第 3 张幻灯片上应用缩放切换效果
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// 设置 7 秒的切换时间
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// 将演示文稿写入磁盘
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [ISlideCollection](../../islidecollection/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)