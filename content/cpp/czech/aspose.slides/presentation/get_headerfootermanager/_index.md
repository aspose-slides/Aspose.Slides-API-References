---
title: get_HeaderFooterManager()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací aktuální správce HeaderFooter. Pouze pro čtení IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /cs/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() metoda

Vrací aktuální správce HeaderFooter. Pouze pro čtení [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Poznámky

Následující příklad ukazuje, jak nastavit viditelnost zápatí uvnitř [Slide](../../slide/) aplikace PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Vlastnost IsFooterVisible se používá k označení, že zástupný prvek zápatí snímku není přítomen.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Metoda SetFooterVisibility se používá k zpřístupnění zástupného prvku zápatí snímku.
    headerFooterManager->SetFooterVisibility(true);
}

// Vlastnost IsSlideNumberVisible se používá k označení, že zástupný prvek čísla stránky snímku není přítomen.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Metoda SetSlideNumberVisibility se používá k zpřístupnění zástupného prvku čísla stránky snímku.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Vlastnost IsDateTimeVisible se používá k označení, že zástupný prvek data a času snímku není přítomen.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Metoda SetFooterVisibility se používá k zpřístupnění zástupného prvku data a času snímku.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Metoda SetFooterText se používá k nastavení textu do zástupného prvku zápatí snímku.
headerFooterManager->SetFooterText(u"Footer text");
// Metoda SetDateTimeText se používá k nastavení textu do zástupného prvku data a času snímku.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
Následující příklad ukazuje, jak nastavit viditelnost podřízeného zápatí uvnitř [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Metoda SetFooterAndChildFootersVisibility se používá k zpřístupnění hlavního snímku a všech podřízených zástupných prvků zápatí.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Metoda SetSlideNumberAndChildSlideNumbersVisibility se používá k zpřístupnění hlavního snímku a všech podřízených zástupných prvků číslování stránek.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Metoda SetDateTimeAndChildDateTimesVisibility se používá k zpřístupnění hlavního snímku a všech podřízených zástupných prvků data a času.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Metoda SetFooterAndChildFootersText se používá k nastavení textu do hlavního snímku a všech podřízených zástupných prvků zápatí.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Metoda SetDateTimeAndChildDateTimesText se používá k nastavení textu do hlavního snímku a všech podřízených zástupných prvků data a času.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* třída [Presentation](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)