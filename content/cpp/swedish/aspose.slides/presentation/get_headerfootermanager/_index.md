---
title: get_HeaderFooterManager()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar faktisk HeaderFooter manager. Skrivskyddad IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /sv/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() metod

Returnerar faktisk HeaderFooter hanterare. Skrivskyddad [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Anmärkningar

Följande exempel visar hur du sätter sidfotsynlighet i [Slide](../../slide/) i PowerPoint [Presentation](../).
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Property IsFooterVisible används för att indikera att en slide footer-placeholder inte finns.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Method SetFooterVisibility används för att göra en slide footer-placeholder synlig.
    headerFooterManager->SetFooterVisibility(true);
}

// Property IsSlideNumberVisible används för att indikera att en slide sidnummer-placeholder inte finns.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Method SetSlideNumberVisibility används för att göra en slide sidnummer-placeholder synlig.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Property IsDateTimeVisible används för att indikera att en slide datum-tid-placeholder inte finns.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Method SetFooterVisibility används för att göra en slide datum-tid-placeholder synlig.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Method SetFooterText används för att sätta text till slide footer-placeholder.
headerFooterManager->SetFooterText(u"Footer text");
// Method SetDateTimeText används för att sätta text till slide datum-tid-placeholder.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 Följande exempel visar hur du sätter barnsidfotsynlighet i [Slide](../../slide/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Metoden SetFooterAndChildFootersVisibility används för att göra en master slide och alla underordnade footer-placeholder synliga.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Metoden SetSlideNumberAndChildSlideNumbersVisibility används för att göra en master slide och alla underordnade sidnummer-placeholder synliga.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Metoden SetDateTimeAndChildDateTimesVisibility används för att göra en master slide och alla underordnade datum-tid-placeholder synliga.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Metoden SetFooterAndChildFootersText används för att sätta text till master slide och alla underordnade footer-placeholder.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Metoden SetDateTimeAndChildDateTimesText används för att sätta text till master slide och alla underordnade datum-tid-placeholder.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)