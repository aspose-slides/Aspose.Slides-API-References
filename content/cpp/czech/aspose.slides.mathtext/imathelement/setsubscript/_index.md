---
title: SetSubscript()
second_title: Aspose.Slides pro C++ API referenční příručka
description: Vytvoří dolní index
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) metoda

Vytvoří dolní index

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dolní index (nižší index vpravo) |

### Návratová hodnota

Nový matematický prvek typu [IMathSubscriptElement](../../imathsubscriptelement/)

## Poznámky

Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) metoda

Vytvoří dolní index

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Dolní index (nižší index vpravo) |

### Návratová hodnota

Nový matematický prvek typu [IMathSubscriptElement](../../imathsubscriptelement/)

## Poznámky

Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathSubscriptElement](../../imathsubscriptelement/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)