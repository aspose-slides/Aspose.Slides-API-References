---
title: SetSubscript()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Tworzy indeks dolny
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) metoda

Tworzy indeks dolny

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Indeks dolny (dolny indeks po prawej) |

### Wartość zwracana

Nowy element matematyczny typu [IMathSubscriptElement](../../imathsubscriptelement/)
## Uwagi



Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) metoda

Tworzy indeks dolny

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Indeks dolny (dolny indeks po prawej) |

### Wartość zwracana

Nowy element matematyczny typu [IMathSubscriptElement](../../imathsubscriptelement/)
## Uwagi



Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathSubscriptElement](../../imathsubscriptelement/)
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)