---
title: get_AlignmentPoint()
second_title: Aspose.Slides pro C++ API Reference
description: "Když je true, tento emulátor operátoru slouží jako zarovnávací bod; tj., určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. Výchozí hodnota: false"
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() metoda


Když je true, tento emulátor operátoru slouží jako zarovnávací bod; tj. určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány. Výchozí hodnota: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## Poznámky


Příklad: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Viz také

* Třída [MathBox](../)
* Obor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)