---
title: get_HeaderFooterManager()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert de werkelijke HeaderFooter manager. Alleen-lezen IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /nl/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() methode


Retourneert de werkelijke HeaderFooter manager. Alleen-lezen [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Opmerkingen


Het volgende voorbeeld laat zien hoe u de voettekstzichtbaarheid instelt binnen [Slide](../../slide/) van PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Eigenschap IsFooterVisible wordt gebruikt om aan te geven dat een dia-voettekstplaceholder niet aanwezig is.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Methode SetFooterVisibility wordt gebruikt om een dia-voettekstplaceholder zichtbaar te maken.
    headerFooterManager->SetFooterVisibility(true);
}

// Eigenschap IsSlideNumberVisible wordt gebruikt om aan te geven dat een dia-paginanummerplaceholder niet aanwezig is.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Methode SetSlideNumberVisibility wordt gebruikt om een dia-paginanummerplaceholder zichtbaar te maken.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Eigenschap IsDateTimeVisible wordt gebruikt om aan te geven dat een dia-datum-tijdplaceholder niet aanwezig is.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Methode SetFooterVisibility wordt gebruikt om een dia-datum-tijdplaceholder zichtbaar te maken.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Methode SetFooterText wordt gebruikt om tekst in te stellen voor de dia-voettekstplaceholder.
headerFooterManager->SetFooterText(u"Footer text");
// Methode SetDateTimeText wordt gebruikt om tekst in te stellen voor de dia-datum-tijdplaceholder.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 Het volgende voorbeeld laat zien hoe u de voettekstzichtbaarheid van een kind instelt binnen [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Methode SetFooterAndChildFootersVisibility wordt gebruikt om een masterdia en alle onderliggende voettekstplaceholders zichtbaar te maken.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Methode SetSlideNumberAndChildSlideNumbersVisibility wordt gebruikt om een masterdia en alle onderliggende paginanummerplaceholders zichtbaar te maken.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Methode SetDateTimeAndChildDateTimesVisibility wordt gebruikt om een masterdia en alle onderliggende datum-tijdplaceholders zichtbaar te maken.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Methode SetFooterAndChildFootersText wordt gebruikt om tekst in te stellen voor de masterdia en alle onderliggende voettekstplaceholders.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Methode SetDateTimeAndChildDateTimesText wordt gebruikt om tekst in te stellen voor de masterdia en alle onderliggende datum-tijdplaceholders.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Klasse [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)