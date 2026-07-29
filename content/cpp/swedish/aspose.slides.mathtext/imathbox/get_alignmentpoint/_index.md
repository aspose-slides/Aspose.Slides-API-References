---
title: get_AlignmentPoint()
second_title: Aspose.Slides för C++ API-referens
description: "När true, fungerar denna operatoremulator som en justeringspunkt; det vill säga, specificerade justeringspunkter i andra ekvationer kan justeras med den. Standard: false"
type: docs
weight: 92
url: /sv/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() metod

När true, fungerar denna operatoremulator som en justeringspunkt; det vill säga, specificerade justeringspunkter i andra ekvationer kan justeras med den. Standard: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```
## Anmärkningar

Exempel:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```
## Se även

* Klass [IMathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)