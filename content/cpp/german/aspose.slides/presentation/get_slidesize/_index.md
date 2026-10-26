---
title: get_SlideSize()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Foliengrößen-Objekt zurück. Schreibgeschützt ISlideSize.
type: docs
weight: 79
url: /de/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() Methode


Gibt ein Foliengrößenobjekt zurück. Schreibgeschützt [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Remarks


Das folgende Beispiel zeigt, wie die Foliengröße in einer PowerPoint [Presentation](../) geändert wird. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 Das folgende Beispiel zeigt, wie die Foliengröße in Bezug auf die Inhalts-Skalierung für eine PowerPoint [Presentation](../) festgelegt wird. 
```cpp
// Instanziiere ein Presentation-Objekt, das eine Präsentationsdatei darstellt
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Setze die Foliengröße der erzeugten Präsentationen auf die der Quelle
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Die Methode SetSize wird verwendet, um die Foliengröße mit Skalierung des Inhalts anzupassen, um die Passform zu gewährleisten
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Die Methode SetSize wird verwendet, um die Foliengröße mit maximaler Größe des Inhalts festzulegen
// Speichere die Präsentation auf dem Datenträger
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 Das folgende Beispiel zeigt, wie benutzerdefinierte Foliengrößen in einer PowerPoint [Presentation](../) angegeben werden. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4-Papiergröße
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlideSize](../../islidesize/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)