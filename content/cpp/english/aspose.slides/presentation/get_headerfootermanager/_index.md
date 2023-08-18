---
title: get_HeaderFooterManager()
second_title: Aspose.Slides for C++ API Reference
description: Returns actual HeaderFooter manager. Read-only IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() method


Returns actual HeaderFooter manager. Read-only [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Remarks


The following example shows how to set footer visibility inside [Slide](../../slide/) of PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Property IsFooterVisible is used for indicating that a slide footer placeholder is not present.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Method SetFooterVisibility is used for making a slide footer placeholder visible.
    headerFooterManager->SetFooterVisibility(true);
}

// Property IsSlideNumberVisible is used for indicating that a slide page number placeholder is not present.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Method SetSlideNumberVisibility is used for making a slide page number placeholder visible.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Property IsDateTimeVisible is used for indicating that a slide date-time placeholder is not present.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Method SetFooterVisibility is used for making a slide date-time placeholder visible.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Method SetFooterText is used for setting text to slide footer placeholder.
headerFooterManager->SetFooterText(u"Footer text");
// Method SetDateTimeText is used for setting text to slide date-time placeholder.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 The following example shows how to set child footer visibility inside [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Method SetFooterAndChildFootersVisibility is used for making a master slide and all child footer placeholders visible.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Method SetSlideNumberAndChildSlideNumbersVisibility is used for making a master slide and all child page number placeholders visible.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Method SetDateTimeAndChildDateTimesVisibility is used for making a master slide and all child date-time placeholders visible.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Method SetFooterAndChildFootersText is used for setting text to master slide and all child footer placeholders.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Method SetDateTimeAndChildDateTimesText is used for setting text to master slide and all child date-time placeholders.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)