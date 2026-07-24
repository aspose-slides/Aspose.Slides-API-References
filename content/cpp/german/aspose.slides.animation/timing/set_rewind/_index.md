---
title: set_Rewind()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieses Attribut gibt an, ob der Effekt nach dem Abspielen zurückspult. Schreiben bool.
type: docs
weight: 248
url: /de/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) Methode


Dieses Attribut gibt an, ob der Effekt nach dem Abspielen zurückspult. Schreiben **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## Hinweise



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Holt die Effektsequenz für die erste Folie
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Holt den ersten Effekt der Hauptsequenz.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Aktiviert das Timing/Rewind des Effekts.
effect->get_Timing()->set_Rewind(true);
```

## Siehe auch

* Klasse [Timing](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)