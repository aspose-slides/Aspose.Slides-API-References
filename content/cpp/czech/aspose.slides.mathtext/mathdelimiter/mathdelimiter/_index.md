---
title: MathDelimiter()
second_title: Aspose.Slides pro C++ API Reference
description: Inicializuje MathDelimiter se zadaným elementem jako jediným základním argumentem
type: docs
weight: 144
url: /cs/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) konstruktor


Inicializuje [MathDelimiter](../) pomocí zadaného elementu jako jediného základního argumentu

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní element, na který se aplikuje oddělovač. Může být null. |
## Poznámky



Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)