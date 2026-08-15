---
title: get_HeaderFooterManager()
second_title: Aspose.Slides for C++ API 參考
description: 傳回實際的 HeaderFooter manager。唯讀 IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /zh-hant/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() 方法


傳回實際的 HeaderFooter manager。唯讀 [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## 備註


以下範例說明如何在 PowerPoint [Presentation](../) 的 [Slide](../../slide/) 中設定頁腳可見性。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Property IsFooterVisible 用於指示投影片頁腳佔位符不存在。
if (!headerFooterManager->get_IsFooterVisible())
{
    // Method SetFooterVisibility 用於使投影片頁腳佔位符可見。
    headerFooterManager->SetFooterVisibility(true);
}

// Property IsSlideNumberVisible 用於指示投影片頁碼佔位符不存在。
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Method SetSlideNumberVisibility 用於使投影片頁碼佔位符可見。
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Property IsDateTimeVisible 用於指示投影片日期時間佔位符不存在。
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Method SetFooterVisibility 用於使投影片日期時間佔位符可見。
    headerFooterManager->SetDateTimeVisibility(true);
}

// Method SetFooterText 用於設定投影片頁腳佔位符的文字。
headerFooterManager->SetFooterText(u"Footer text");
// Method SetDateTimeText 用於設定投影片日期時間佔位符的文字。
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 以下範例說明如何在 [Slide](../../slide/) 中設定子頁腳可見性。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// 方法 SetFooterAndChildFootersVisibility 用於使母投影片及所有子頁腳佔位符可見。
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// 方法 SetSlideNumberAndChildSlideNumbersVisibility 用於使母投影片及所有子頁碼佔位符可見。
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// 方法 SetDateTimeAndChildDateTimesVisibility 用於使母投影片及所有子日期時間佔位符可見。
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// 方法 SetFooterAndChildFootersText 用於設定母投影片及所有子頁腳佔位符的文字。
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// 方法 SetDateTimeAndChildDateTimesText 用於設定母投影片及所有子日期時間佔位符的文字。
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)