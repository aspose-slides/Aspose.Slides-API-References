---
title: get_HeaderFooterManager()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den aktuellen HeaderFooter-Manager zurück. Nur lesbar IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /de/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() Methode

Gibt den aktuellen HeaderFooter-Manager zurück. Nur lesbar [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Bemerkungen

Das folgende Beispiel zeigt, wie man die Sichtbarkeit der Fußzeile innerhalb von [Slide](../../slide/) von PowerPoint [Presentation](../) einstellt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Property IsFooterVisible wird verwendet, um anzuzeigen, dass ein Folienfußzeilen-Platzhalter nicht vorhanden ist.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Method SetFooterVisibility wird verwendet, um einen Folienfußzeilen-Platzhalter sichtbar zu machen.
    headerFooterManager->SetFooterVisibility(true);
}

// Property IsSlideNumberVisible wird verwendet, um anzuzeigen, dass ein Folienseitenzahlen-Platzhalter nicht vorhanden ist.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Method SetSlideNumberVisibility wird verwendet, um einen Folienseitenzahlen-Platzhalter sichtbar zu machen.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Property IsDateTimeVisible wird verwendet, um anzuzeigen, dass ein Foliendatum-Uhrzeit-Platzhalter nicht vorhanden ist.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Method SetFooterVisibility wird verwendet, um einen Foliendatum-Uhrzeit-Platzhalter sichtbar zu machen.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Method SetFooterText wird verwendet, um Text für den Folienfußzeilen-Platzhalter zu setzen.
headerFooterManager->SetFooterText(u"Footer text");
// Method SetDateTimeText wird verwendet, um Text für den Foliendatum-Uhrzeit-Platzhalter zu setzen.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 Das folgende Beispiel zeigt, wie man die Sichtbarkeit der untergeordneten Fußzeile innerhalb von [Slide](../../slide/) einstellt. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Methode SetFooterAndChildFootersVisibility wird verwendet, um einen Master-Folie und alle untergeordneten Fußzeilen-Platzhalter sichtbar zu machen.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Methode SetSlideNumberAndChildSlideNumbersVisibility wird verwendet, um einen Master-Folie und alle untergeordneten Seitenzahlen-Platzhalter sichtbar zu machen.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Methode SetDateTimeAndChildDateTimesVisibility wird verwendet, um einen Master-Folie und alle untergeordneten Datum-Uhrzeit-Platzhalter sichtbar zu machen.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Methode SetFooterAndChildFootersText wird verwendet, um Text für die Master-Folie und alle untergeordneten Fußzeilen-Platzhalter zu setzen.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Methode SetDateTimeAndChildDateTimesText wird verwendet, um Text für die Master-Folie und alle untergeordneten Datum-Uhrzeit-Platzhalter zu setzen.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)