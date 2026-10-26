---
title: set_SufficientResolution()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví hodnotu určující rozlišení obrázků v PDF dokumentu.
type: docs
weight: 365
url: /cs/aspose.slides.export/pdfoptions/set_sufficientresolution/
---
## PdfOptions::set_SufficientResolution(float) method

Nastaví hodnotu určující rozlišení obrázků uvnitř PDF dokumentu.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SufficientResolution(float value) override
```

## Poznámky

Vlastnost ovlivňuje velikost souboru, dobu exportu a kvalitu obrazu.

Výchozí hodnota je **96**.

Účinek tohoto parametru závisí na několika faktorech. Algoritmus se snaží získat nejlepší velikost výstupního obrázku podle hodnoty vlastnosti, velikosti zdrojového obrázku a velikosti rámce obrázku. Použití podobných hodnot vlastnosti může dát stejný výsledek. Doporučuje se použít krok 16 nebo 32 pro dosažení viditelného efektu.

Zapište **float**. 
## Viz také

* Třída [PdfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)