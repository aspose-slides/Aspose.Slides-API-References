---
title: ToBox()
second_title: Aspose.Slides für C++ API-Referenz
description: Platziert dieses Element in einem nicht-visuellen Kasten (logische Gruppierung), der verwendet wird, um Komponenten einer Gleichung oder einer anderen Instanz mathematischen Textes zu gruppieren. Ein gekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind.
type: docs
weight: 261
url: /de/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() Methode


Platziert dieses Element in einem unsichtbaren Kasten (logische Gruppierung), der verwendet wird, um Komponenten einer Gleichung oder anderer Instanzen mathematischen Textes zu gruppieren. Ein gekapseltes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass innerhalb keine Zeilenumbrüche erlaubt sind.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### Rückgabewert

Logischer Kasten, in dem dieses Element platziert ist
## Bemerkungen



Beispiel: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBox](../../imathbox/)
* Klasse [MathElementBase](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)