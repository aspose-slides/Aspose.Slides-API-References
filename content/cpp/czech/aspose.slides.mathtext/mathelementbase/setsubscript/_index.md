---
title: SetSubscript()
second_title: Aspose.Slides pro C++ API Reference
description: Vytváří dolní index
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) metoda


Vytváří dolní index

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolní index (nižší index vpravo) |

### Návratová hodnota

Nový matematický prvek typu [IMathSubscriptElement](../../imathsubscriptelement/)
## Poznámky



Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) metoda


Vytváří dolní index

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
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
* třída [IMathSubscriptElement](../../imathsubscriptelement/)
* třída [IMathElement](../../imathelement/)
* třída [MathElementBase](../)
* třída [String](../../../system/string/)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)