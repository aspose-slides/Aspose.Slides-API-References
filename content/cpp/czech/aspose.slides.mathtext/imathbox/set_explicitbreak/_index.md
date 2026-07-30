---
title: set_ExplicitBreak()
second_title: Aspose.Slides pro C++ – API reference
description: "Explicitní přerušení určuje, zda na začátku objektu Box existuje zalomení řádku, takže řádek zalamuje na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, který bude použit jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní přerušení)"
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) metoda

Explicitní přerušení určuje, zda na začátku objektu Box existuje zalomení řádku, takže řádek zalamuje na začátku objektu Box. Určuje číslo operátoru na předchozím řádku matematického textu, který bude použit jako zarovnávací bod pro aktuální řádek matematického textu. Možné hodnoty: 1..255 Výchozí: 0 (žádné explicitní přerušení)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
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