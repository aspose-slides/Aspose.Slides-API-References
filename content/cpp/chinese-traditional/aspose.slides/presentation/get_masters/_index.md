---
title: get_Masters()
second_title: Aspose.Slides for C++ API 參考
description: 傳回在簡報中定義的所有母片投影片的清單。唯讀 IMasterSlideCollection.
type: docs
weight: 118
url: /zh-hant/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() 方法

傳回在簡報中定義的所有母片投影片的清單。唯讀 [IMasterSlideCollection](../../imasterslidecollection/)。

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## 備註

以下範例說明如何將 [Images](../../images/) 新增至 PowerPoint [Presentation](../) 的母片 [Slides](../../)。 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
以下範例說明如何變更 PowerPoint [Presentation](../) 的母片投影片背景顏色。 
```cpp
// 實例化代表簡報檔案的 Presentation 類別
auto pres = System::MakeObject<Presentation>();

// 設定 Master ISlide 的背景顏色為森林綠
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// 將簡報寫入磁碟
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
以下範例說明如何將投影片版面配置新增至 PowerPoint [Presentation](../)。 
```cpp
// 實例化代表簡報檔案的 Presentation 類別
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// 嘗試依版面投影片類型搜尋
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // 簡報不包含某些類型版面的情況。
    // 簡報檔案僅包含 Blank 和 Custom 版面類型。
    // 但是具有 Custom 類型的版面投影片有不同的投影片名稱，
    // 例如 "Title", "Title and Content", etc. And it is possible to use these
    // 名稱來選取版面投影片。
    // 也可以使用佔位圖形類型的集合。例如，
    // Title slide should have only Title plec...
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

// 使用新增的版面投影片添加空白投影片
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// 儲存簡報
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* class [IMasterSlideCollection](../../imasterslidecollection/)
* class [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)