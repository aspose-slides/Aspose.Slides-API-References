---
title: get_HeaderFooterManager()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il gestore HeaderFooter attuale. Solo lettura IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /it/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() metodo

Restituisce il gestore HeaderFooter attuale. Solo lettura [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Osservazioni

Il seguente esempio mostra come impostare la visibilità del piè di pagina all'interno di [Slide](../../slide/) di PowerPoint [Presentation](../).
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// La proprietà IsFooterVisible è usata per indicare che il segnaposto del piè di pagina della diapositiva non è presente.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Il metodo SetFooterVisibility è usato per rendere visibile il segnaposto del piè di pagina della diapositiva.
    headerFooterManager->SetFooterVisibility(true);
}

// La proprietà IsSlideNumberVisible è usata per indicare che il segnaposto del numero di pagina della diapositiva non è presente.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Il metodo SetSlideNumberVisibility è usato per rendere visibile il segnaposto del numero di pagina della diapositiva.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// La proprietà IsDateTimeVisible è usata per indicare che il segnaposto della data e ora della diapositiva non è presente.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Il metodo SetFooterVisibility è usato per rendere visibile il segnaposto della data e ora della diapositiva.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Il metodo SetFooterText è usato per impostare il testo nel segnaposto del piè di pagina della diapositiva.
headerFooterManager->SetFooterText(u"Footer text");
// Il metodo SetDateTimeText è usato per impostare il testo nel segnaposto della data e ora della diapositiva.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 Il seguente esempio mostra come impostare la visibilità del piè di pagina figlio all'interno di [Slide](../../slide/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Il metodo SetFooterAndChildFootersVisibility è usato per rendere visibile la diapositiva master e tutti i segnaposti del piè di pagina figlio.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Il metodo SetSlideNumberAndChildSlideNumbersVisibility è usato per rendere visibile la diapositiva master e tutti i segnaposti del numero di pagina figlio.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Il metodo SetDateTimeAndChildDateTimesVisibility è usato per rendere visibile la diapositiva master e tutti i segnaposti della data-ora figlio.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Il metodo SetFooterAndChildFootersText è usato per impostare il testo nella diapositiva master e in tutti i segnaposti del piè di pagina figlio.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Il metodo SetDateTimeAndChildDateTimesText è usato per impostare il testo nella diapositiva master e in tutti i segnaposti della data-ora figlio.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* classe [Presentation](../)
* namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)