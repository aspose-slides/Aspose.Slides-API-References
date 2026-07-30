---
title: ToBox()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Umístí tento prvek do neviditelného boxu (logického seskupení), který se používá k seskupení komponent rovnice nebo jiného výskytu matematického textu. Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku nebo být seskupen tak, aby neumožňoval vnitřní zalomení řádků.
type: docs
weight: 261
url: /cs/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() metoda

Umístí tento prvek do neviditelného boxu (logického seskupení), který se používá k seskupení komponent rovnice nebo jiného výskytu matematického textu. Boxovaný objekt může (například) sloužit jako emulátor operátoru s nebo bez zarovnávacího bodu, sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádku uvnitř.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```

### Návratová hodnota

Logický box s tímto umístěným prvkem uvnitř

## Poznámky



Příklad: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathBox](../../imathbox/)
* třída [MathElementBase](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)