---
title: get_Masters()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションで定義されているすべてのマスタースライドの一覧を返します。読み取り専用 IMasterSlideCollection.
type: docs
weight: 118
url: /ja/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() メソッド


プレゼンテーションで定義されているすべてのマスタースライドの一覧を返します。 読み取り専用 [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## 備考


次の例は、PowerPoint [Presentation](../) のマスター [Slides](../../) に [Images](../../images/) を追加する方法を示します。 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 次の例は、PowerPoint [Presentation](../) のマスタースライドの背景色を変更する方法を示します。 
```cpp
// プレゼンテーションファイルを表す Presentation クラスのインスタンスを作成します
auto pres = System::MakeObject<Presentation>();

// マスター ISlide の背景色をフォレストグリーンに設定します
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// プレゼンテーションをディスクに保存します
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 次の例は、PowerPoint [Presentation](../) にスライドレイアウトを追加する方法を示します。 
```cpp
// プレゼンテーションファイルを表す Presentation クラスのインスタンスを作成します
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// レイアウトスライドのタイプで検索を試みます
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // プレゼンテーションに特定のタイプのレイアウトが含まれていない状況です。
    // プレゼンテーションファイルには Blank と Custom のレイアウトタイプしか含まれていません。
    // ただし、Custom タイプのレイアウトスライドは異なるスライド名を持ちます、
    // たとえば "Title", "Title and Content" などです。これらを使用することも可能です
    // レイアウトスライドの選択に使用できます。
    // また、プレースホルダーシェイプタイプのセットを使用することも可能です。例として、
    // タイトルスライドは Title プレースホルダータイプのみを持つべきです、など。
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

// 追加したレイアウトスライドで空のスライドを挿入します
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// プレゼンテーションを保存します
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMasterSlideCollection](../../imasterslidecollection/)
* クラス [Presentation](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)