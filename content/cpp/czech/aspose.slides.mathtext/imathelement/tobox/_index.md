---
title: ToBox()
second_title: Aspose.Slides pro C++ API Reference
description: Umístí tento prvek do neviditelného boxu (logické seskupení), který se používá k seskupení komponent rovnice nebo jiné instance matematického textu. Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř.
type: docs
weight: 274
url: /cs/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() method

Umístí tento prvek do neviditelného boxu (logické seskupení), který se používá k seskupení komponent rovnice nebo jiné instance matematického textu. Boxovaný objekt může (například) sloužit jako emulátor operátoru s- nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### Návratová hodnota

Logický box s tímto prvkem umístěným uvnitř
## Poznámky



Příklad: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBox](../../imathbox/)
* Třída [IMathElement](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)