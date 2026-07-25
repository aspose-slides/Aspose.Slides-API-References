---
title: get_HeaderFooterManager()
second_title: Aspose.Slides for C++ API リファレンス
description: 実際の HeaderFooter マネージャーを返します。読み取り専用 IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /ja/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() メソッド


実際の HeaderFooter マネージャーを返します。読み取り専用 [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## 備考


次の例は、PowerPoint [Presentation](../) の [Slide](../../slide/) 内でフッターの表示を設定する方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// プロパティ IsFooterVisible は、スライドのフッタープレースホルダーが存在しないことを示すために使用されます。
if (!headerFooterManager->get_IsFooterVisible())
{
    // メソッド SetFooterVisibility は、スライドのフッタープレースホルダーを表示できるようにするために使用されます。
    headerFooterManager->SetFooterVisibility(true);
}

// プロパティ IsSlideNumberVisible は、スライドのページ番号プレースホルダーが存在しないことを示すために使用されます。
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // メソッド SetSlideNumberVisibility は、スライドのページ番号プレースホルダーを表示できるようにするために使用されます。
    headerFooterManager->SetSlideNumberVisibility(true);
}

// プロパティ IsDateTimeVisible は、スライドの日時プレースホルダーが存在しないことを示すために使用されます。
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // メソッド SetFooterVisibility は、スライドの日時プレースホルダーを表示できるようにするために使用されます。
    headerFooterManager->SetDateTimeVisibility(true);
}

// メソッド SetFooterText は、スライドのフッタープレースホルダーにテキストを設定するために使用されます。
headerFooterManager->SetFooterText(u"Footer text");
// メソッド SetDateTimeText は、スライドの日時プレースホルダーにテキストを設定するために使用されます。
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 次の例は、[Slide](../../slide/) 内で子フッターの表示を設定する方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// メソッド SetFooterAndChildFootersVisibility は、マスタースライドとすべての子フッタープレースホルダーを表示できるようにするために使用されます。
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// メソッド SetSlideNumberAndChildSlideNumbersVisibility は、マスタースライドとすべての子ページ番号プレースホルダーを表示できるようにするために使用されます。
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// メソッド SetDateTimeAndChildDateTimesVisibility は、マスタースライドとすべての子日時プレースホルダーを表示できるようにするために使用されます。
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// メソッド SetFooterAndChildFootersText は、マスタースライドとすべての子フッタープレースホルダーにテキストを設定するために使用されます。
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// メソッド SetDateTimeAndChildDateTimesText は、マスタースライドとすべての子日時プレースホルダーにテキストを設定するために使用されます。
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* クラス [Presentation](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)