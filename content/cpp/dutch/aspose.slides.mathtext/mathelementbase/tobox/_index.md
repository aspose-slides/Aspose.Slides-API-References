---
title: ToBox()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaatst dit element in een niet-visuele doos (logische groepering) die wordt gebruikt om componenten van een vergelijking of een andere instantie van wiskundige tekst te groeperen. Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of worden gegroepeerd zodat er binnen geen regeleinden worden toegestaan.
type: docs
weight: 261
url: /nl/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() methode

Plaatst dit element in een niet-visuele doos (logische groepering) die wordt gebruikt om componenten van een vergelijking of een andere instantie van wiskundige tekst te groeperen. Een ingesloten object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of worden gegroepeerd zodat er geen regeleinden binnen worden toegestaan.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```

### Retourwaarde

Logische doos met dit element erin geplaatst

## Opmerkingen

Voorbeeld:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBox](../../imathbox/)
* Klasse [MathElementBase](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)