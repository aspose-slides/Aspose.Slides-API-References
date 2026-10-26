---
title: get_Masters()
second_title: Aspose.Slides for C++ API 参考
description: 返回在演示文稿中定义的所有母版幻灯片的列表。只读 IMasterSlideCollection.
type: docs
weight: 118
url: /zh/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() 方法

返回在演示文稿中定义的所有母版幻灯片的列表。只读 [IMasterSlideCollection](../../imasterslidecollection/)。

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## 备注

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
以下示例展示了如何将 [Images](../../images/) 添加到 PowerPoint [Presentation](../) 的 Master [Slides](../../)。

```cpp
// 实例化表示演示文稿文件的 Presentation 类
auto pres = System::MakeObject<Presentation>();

// 将母版 ISlide 的背景颜色设置为森林绿
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// 将演示文稿写入磁盘
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
以下示例展示了如何更改 PowerPoint [Presentation](../) 母版幻灯片的背景颜色。

```cpp
// 实例化表示演示文稿文件的 Presentation 类
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// 尝试按布局幻灯片类型搜索
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // 演示文稿不包含某些类型布局的情况。
    // 演示文稿文件仅包含 Blank 和 Custom 布局类型。
    // 但具有 Custom 类型的布局幻灯片有不同的幻灯片名称，
    // 例如 "Title", "Title and Content" 等，并且可以使用这些
    // 名称来选择布局幻灯片。
    // 同样也可以使用占位符形状类型的集合。例如，
    // 标题幻灯片应仅有 Title 占位符类型，等等。
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// 使用添加的布局幻灯片插入空白幻灯片
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// 保存演示文稿
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```
以下示例展示了如何向 PowerPoint [Presentation](../) 添加幻灯片布局。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlideCollection](../../imasterslidecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)