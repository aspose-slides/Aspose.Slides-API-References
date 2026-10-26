---
title: MathDelimiter()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert MathDelimiter met het opgegeven element als enkel basisargument
type: docs
weight: 144
url: /nl/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) constructor

Initialiseert [MathDelimiter](../) met het opgegeven element als enkel basisargument

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het basiselement waarop de delimiter wordt toegepast. Kan null zijn. |
## Opmerkingen



Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)