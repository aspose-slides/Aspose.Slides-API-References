---
title: set_ExplicitBreak()
second_title: Aspose.Slides pro C++ API Reference
description: "Explicit break určuje, zda na začátku objektu Box existuje koncová značka řádku, takže řádek se zalamuje na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, které má být použito jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní zalomení)"
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) metoda


Explicitní zalomení určuje, zda na začátku objektu Box existuje koncová značka řádku, takže řádek zalamuje na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, které má být použito jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní zalomení)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## Poznámky


Příklad:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Viz také

* Třída [MathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)