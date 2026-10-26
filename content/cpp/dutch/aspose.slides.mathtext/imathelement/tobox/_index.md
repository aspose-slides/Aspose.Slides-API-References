---
title: ToBox()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaatst dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of een andere instantie van wiskundige tekst te groeperen. Een ingekapseld object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of gegroepeerd worden zodat regelbreuken binnen het object niet worden toegestaan.
type: docs
weight: 274
url: /nl/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() methode


Plaatst dit element in een niet-visuele box (logische groepering) die wordt gebruikt om componenten van een vergelijking of een andere instance van wiskundige tekst te groeperen. Een ingekapseld object kan (bijvoorbeeld) dienen als een operator-emulator met of zonder een uitlijningspunt, dienen als een regeleinde-punt, of gegroepeerd worden zodat regelbreuken binnen het object niet worden toegestaan.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```


### Retourwaarde

Logische box met dit element erin geplaatst
## Opmerkingen



Voorbeeld: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBox](../../imathbox/)
* Klasse [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)