---
title: get_HeaderFooterManager()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a tényleges HeaderFooter kezelőt. Csak olvasható IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /hu/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() metódus

Visszaadja a tényleges HeaderFooter kezelőt. Csak olvasható [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Megjegyzések

A következő példa azt mutatja, hogyan állítható be a lábléc láthatósága a [Slide](../../slide/) belsejében a PowerPoint [Presentation](../)-ban. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Az IsFooterVisible tulajdonságot arra használják, hogy jelezzék, egy diának nincs lábléchelyőrzője.
if (!headerFooterManager->get_IsFooterVisible())
{
    // A SetFooterVisibility metódus arra szolgál, hogy egy diának lábléchelyőrzőjét láthatóvá tegye.
    headerFooterManager->SetFooterVisibility(true);
}

// Az IsSlideNumberVisible tulajdonságot arra használják, hogy jelezzék, egy diának nincs oldalszámhelyőrzője.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // A SetSlideNumberVisibility metódus arra szolgál, hogy egy diának oldalszámhelyőrzőjét láthatóvá tegye.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Az IsDateTimeVisible tulajdonságot arra használják, hogy jelezzék, egy diának nincs dátum-időhelyőrzője.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // A SetFooterVisibility metódust arra használják, hogy egy diának dátum-időhelyőrzőjét láthatóvá tegye.
    headerFooterManager->SetDateTimeVisibility(true);
}

// A SetFooterText metódus arra szolgál, hogy szöveget állítson be a dia lábléchelyőrzőjébe.
headerFooterManager->SetFooterText(u"Footer text");
// A SetDateTimeText metódus arra szolgál, hogy szöveget állítson be a dia dátum-időhelyőrzőjébe.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 A következő példa azt mutatja, hogyan állítható be a gyerek lábléc láthatósága a [Slide](../../slide/) belsejében. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// A SetFooterAndChildFootersVisibility metódus arra szolgál, hogy egy mester diát és az összes gyermek lábléchelyőrzőjét láthatóvá tegye.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// A SetSlideNumberAndChildSlideNumbersVisibility metódus arra szolgál, hogy egy mester diát és az összes gyermek oldalszámhelyőrzőjét láthatóvá tegye.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// A SetDateTimeAndChildDateTimesVisibility metódus arra szolgál, hogy egy mester diát és az összes gyermek dátum-időhelyőrzőjét láthatóvá tegye.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// A SetFooterAndChildFootersText metódus arra szolgál, hogy szöveget állítson be a mester diára és az összes gyermek lábléchelyőrzőjére.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// A SetDateTimeAndChildDateTimesText metódus arra szolgál, hogy szöveget állítson be a mester diára és az összes gyermek dátum-időhelyőrzőjére.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)