---
title: get_ExplicitBreak()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Explicit break určuje, zda na začátku objektu Box existuje zalomení řádku, takže řádek se zalamuje na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, které má být použito jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (no explicit break)"
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() metoda


Explicit break určuje, zda na začátku objektu Box existuje zalomení řádku, takže řádek se zalamuje na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, které bude použito jako zarovnávací bod pro aktuální řádek matematického textu možná hodnota: 1..255 Výchozí: 0 (no explicit break)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Poznámky


Příklad: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Viz také

* Třída [IMathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)