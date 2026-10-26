---
title: get_Rewind()
second_title: Aspose.Slides för C++ API-referens
description: Detta attribut specificerar om effekten ska spolas tillbaka när den är klar med uppspelning. Läs bool.
type: docs
weight: 235
url: /sv/aspose.slides.animation/timing/get_rewind/
---
## Timing::get_Rewind() metod


Detta attribut specificerar om effekten spolas tillbaka när den är klar med uppspelning. Läs **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_Rewind() override
```

## Anmärkningar



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Hämta effektssekvensen för den första bilden
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Hämta den första effekten i huvudsekvensen.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Aktivera Timing/Rewind för effekten.
effect->get_Timing()->set_Rewind(true);
```

## Se också

* Klass [Timing](../)
* Namnrymd [Aspose::Slides::Animation](../../)
* Bibliotek [Aspose.Slides](../../../)