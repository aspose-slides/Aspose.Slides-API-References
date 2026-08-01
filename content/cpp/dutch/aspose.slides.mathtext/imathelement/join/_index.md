---
title: Join()
second_title: Aspose.Slides voor C++ API Referentie
description: Voegt een wiskundig element samen en vormt een wiskundig blok
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) methode


Voegt een wiskundig element samen en vormt een wiskundig blok

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Het element dat wordt samengevoegd |

### Retourwaarde

Een nieuw [IMathBlock](../../imathblock/) dat deze instantie en het opgegeven argument bevat
## Opmerkingen



Voorbeeld: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) methode


Voegt een wiskundige tekst samen en vormt een wiskundig blok

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Wiskundige tekst om te voegen |

### Retourwaarde

Een nieuw [IMathBlock](../../imathblock/) dat deze instantie en het opgegeven argument bevat
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)