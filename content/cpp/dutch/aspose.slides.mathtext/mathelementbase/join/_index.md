---
title: Join()
second_title: Aspose.Slides voor C++ API Referentie
description: Voegt een wiskundig element samen en vormt een wiskundig blok
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) methode

Voegt een wiskundig element samen en vormt een wiskundig blok

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het element dat moet worden samengevoegd |

### Retourwaarde

Een nieuw [IMathBlock](../../imathblock/) dat deze instantie en het opgegeven argument bevat
## Opmerkingen



Voorbeeld: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) methode


Voegt een wiskundige tekst samen en vormt een wiskundig blok

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Wiskundige tekst die moet worden samengevoegd |

### Retourwaarde

Een nieuw [IMathBlock](../../imathblock/) dat deze instantie en het opgegeven argument bevat
## Opmerkingen



Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)