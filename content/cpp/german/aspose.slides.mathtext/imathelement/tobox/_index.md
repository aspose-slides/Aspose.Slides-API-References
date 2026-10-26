---
title: ToBox()
second_title: Aspose.Slides für C++ API-Referenz
description: Platziert dieses Element in einem nicht-visuellen Kasten (logische Gruppierung), der verwendet wird, um Komponenten einer Gleichung oder eines anderen mathematischen Textes zu gruppieren. Ein gekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche zulässig sind.
type: docs
weight: 274
url: /de/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() Methode

Platziert dieses Element in einem nicht-visuellen Kasten (logische Gruppierung), der verwendet wird, um Komponenten einer Gleichung oder eines anderen mathematischen Textes zu gruppieren. Ein gekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass Zeilenumbrüche innerhalb nicht zulässig sind.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### Rückgabewert

Logischer Kasten mit diesem Element darin platziert

## Anmerkungen



Beispiel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBox](../../imathbox/)
* Klasse [IMathElement](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)