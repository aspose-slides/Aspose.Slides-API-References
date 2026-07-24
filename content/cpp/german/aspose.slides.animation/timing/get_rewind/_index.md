---
title: get_Rewind()
second_title: Aspose.Slides für C++ API-Referenz
description: Dieses Attribut gibt an, ob der Effekt nach dem Abspielen zurückgespult wird. Lesen bool.
type: docs
weight: 235
url: /de/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() Methode

Dieses Attribut gibt an, ob der Effekt beim Abspielen zurückgespult wird. Lesen **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## Anmerkungen

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hole die Effektsequenz für die erste Folie
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Hole den ersten Effekt der Hauptsequenz.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Aktiviere das Timing/Rewind des Effekts.
effect->get_Timing()->set_Rewind(true);
```

## Siehe auch

* Klasse [Timing](../)
* Namensraum [Aspose::Slides::Animation](../../)
* Bibliothek [Aspose.Slides](../../../)