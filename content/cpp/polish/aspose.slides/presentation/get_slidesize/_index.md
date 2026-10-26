---
title: get_SlideSize()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca obiekt rozmiaru slajdu. Tylko do odczytu ISlideSize.
type: docs
weight: 79
url: /pl/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() metoda


Zwraca obiekt rozmiaru slajdu. Tylko do odczytu [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Uwagi


 Poniższy przykład pokazuje, jak zmienić rozmiar slajdu w PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 Poniższy przykład pokazuje, jak ustawić rozmiar slajdu z uwzględnieniem skalowania zawartości w PowerPoint [Presentation](../). 
```cpp
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Ustaw rozmiar slajdu wygenerowanych prezentacji na taki sam jak w źródle
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Metoda SetSize jest używana do ustawiania rozmiaru slajdu z skalowaniem zawartości, aby zapewnić dopasowanie
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Metoda SetSize jest używana do ustawiania rozmiaru slajdu z maksymalizacją rozmiaru zawartości
// Zapisz prezentację na dysku
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 Poniższy przykład pokazuje, jak określić własne rozmiary slajdów w PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// Rozmiar papieru A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlideSize](../../islidesize/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)