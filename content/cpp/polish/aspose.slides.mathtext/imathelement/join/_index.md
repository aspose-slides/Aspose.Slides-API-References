---
title: Join()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Łączy element matematyczny i tworzy blok matematyczny
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) metoda


Łączy element matematyczny i tworzy blok matematyczny

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Element, który ma być połączony |

### Wartość zwracana

Nowy [IMathBlock](../../imathblock/) zawierający tę instancję i podany argument
## Uwagi



Przykład: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) metoda


Łączy tekst matematyczny i tworzy blok matematyczny

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Tekst matematyczny do połączenia |

### Wartość zwracana

Nowy [IMathBlock](../../imathblock/) zawierający tę instancję i podany argument
## Uwagi



Przykład: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)