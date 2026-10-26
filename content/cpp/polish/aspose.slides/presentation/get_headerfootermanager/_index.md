---
title: get_HeaderFooterManager()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca aktualny menedżer HeaderFooter. Tylko do odczytu IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /pl/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() metoda


Zwraca aktualny menedżer HeaderFooter. Tylko do odczytu [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Uwagi


Poniższy przykład pokazuje, jak ustawić widoczność stopki wewnątrz [Slide](../../slide/) programu PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Właściwość IsFooterVisible jest używana do wskazania, że placeholder stopki slajdu nie jest obecny.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Metoda SetFooterVisibility jest używana do uczynienia placeholdera stopki slajdu widocznym.
    headerFooterManager->SetFooterVisibility(true);
}

// Właściwość IsSlideNumberVisible jest używana do wskazania, że placeholder numeru strony slajdu nie jest obecny.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Metoda SetSlideNumberVisibility jest używana do uczynienia placeholdera numeru strony slajdu widocznym.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Właściwość IsDateTimeVisible jest używana do wskazania, że placeholder daty i czasu slajdu nie jest obecny.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Metoda SetFooterVisibility jest używana do uczynienia placeholdera daty i czasu slajdu widocznym.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Metoda SetFooterText jest używana do ustawiania tekstu w placeholderze stopki slajdu.
headerFooterManager->SetFooterText(u"Footer text");
// Metoda SetDateTimeText jest używana do ustawiania tekstu w placeholderze daty i czasu slajdu.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 Poniższy przykład pokazuje, jak ustawić widoczność stopki podrzędnej wewnątrz [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Metoda SetFooterAndChildFootersVisibility jest używana do uczynienia placeholderów stopki master slajdu i wszystkich podległych widocznymi.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Metoda SetSlideNumberAndChildSlideNumbersVisibility jest używana do uczynienia placeholderów numeru strony master slajdu i wszystkich podległych widocznymi.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Metoda SetDateTimeAndChildDateTimesVisibility jest używana do uczynienia placeholderów daty i czasu master slajdu i wszystkich podległych widocznymi.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Metoda SetFooterAndChildFootersText jest używana do ustawiania tekstu w master slajdzie i wszystkich podległych placeholderach stopki.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Metoda SetDateTimeAndChildDateTimesText jest używana do ustawiania tekstu w master slajdzie i wszystkich podległych placeholderach daty i czasu.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)