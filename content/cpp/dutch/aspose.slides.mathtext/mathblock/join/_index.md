---
title: Join()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een wiskundig element toe aan dit wiskundige blok
type: docs
weight: 183
url: /nl/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) methode


Voegt een wiskundig element toe aan dit wiskundige blok

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het element dat moet worden samengevoegd |

### Retourwaarde

De huidige instantie van [IMathBlock](../../imathblock/)
## Opmerkingen



Voorbeeld: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) methode


Voegt een wiskundige tekst toe aan dit wiskundige blok

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Wiskundige tekst die moet worden samengevoegd |

### Retourwaarde

Een nieuwe [IMathBlock](../../imathblock/) die deze instantie en het opgegeven argument bevat
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBlock](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)