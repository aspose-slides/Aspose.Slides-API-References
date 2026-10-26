---
title: SetSubscript()
second_title: Odwołanie API Aspose.Slides dla C++
description: Tworzy indeks dolny
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) metoda

Tworzy indeks dolny

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscript (lower index on the right) |

### Wartość zwracana

Nowy element matematyczny typu [IMathSubscriptElement](../../imathsubscriptelement/)

## Uwagi



Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) metoda

Tworzy indeks dolny

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the right) |

### Wartość zwracana

Nowy element matematyczny typu [IMathSubscriptElement](../../imathsubscriptelement/)

## Uwagi



Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathSubscriptElement](../../imathsubscriptelement/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathElementBase](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)