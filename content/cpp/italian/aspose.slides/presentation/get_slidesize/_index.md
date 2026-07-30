---
title: get_SlideSize()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'oggetto dimensione della diapositiva. Sola lettura ISlideSize.
type: docs
weight: 79
url: /it/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() metodo

Restituisce l'oggetto slide size. Sola lettura [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Osservazioni

Il seguente esempio mostra come modificare la dimensione della diapositiva in un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
Il seguente esempio mostra come impostare la dimensione della diapositiva rispetto al ridimensionamento del contenuto per un PowerPoint [Presentation](../). 
```cpp
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Imposta la dimensione della diapositiva delle presentazioni generate a quella di origine
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Il metodo SetSize è usato per impostare la dimensione della diapositiva con scala del contenuto per garantire la vestibilità
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Il metodo SetSize è usato per impostare la dimensione della diapositiva massimizzando la dimensione del contenuto
// Salva la presentazione su disco
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
Il seguente esempio mostra come specificare dimensioni della diapositiva personalizzate in un PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// Dimensione carta A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlideSize](../../islidesize/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)