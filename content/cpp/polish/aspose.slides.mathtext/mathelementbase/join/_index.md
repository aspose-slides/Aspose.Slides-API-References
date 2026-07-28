---
title: Join()
second_title: Aspose.Slides dla C++ – referencja API
description: Łączy element matematyczny i tworzy blok matematyczny
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) metoda

Łączy element matematyczny i tworzy blok matematyczny

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element do połączenia |

### Wartość zwracana

Nowy [IMathBlock](../../imathblock/) zawierający tę instancję i określony argument

## Uwagi

Przykład: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) metoda

Łączy tekst matematyczny i tworzy blok matematyczny

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Tekst matematyczny do połączenia |

### Wartość zwracana

Nowy [IMathBlock](../../imathblock/) zawierający tę instancję i określony argument

## Uwagi

Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathElementBase](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)