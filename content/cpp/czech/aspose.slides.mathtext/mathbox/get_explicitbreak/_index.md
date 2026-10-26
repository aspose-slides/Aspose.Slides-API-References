---
title: get_ExplicitBreak()
second_title: Aspose.Slides pro C++ API Reference
description: "Explicitní přerušení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek přeteče na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, který má být použit jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní přerušení)"
type: docs
weight: 118
url: /cs/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() metoda

Explicitní přerušení určuje, zda je na začátku objektu Box zalomení řádku, takže řádek přeteče na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, které má být použito jako zarovnávací bod pro aktuální řádek matematického textu. možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní zalomení)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
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