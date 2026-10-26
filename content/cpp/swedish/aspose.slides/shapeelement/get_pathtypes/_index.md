---
title: get_PathTypes()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en array av bytevärden som specificerar typen för varje punkt i elementets bana.
type: docs
weight: 27
url: /sv/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() metod

Hämtar en array av bytevärden som specificerar typen för varje punkt i elementets bana.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Anmärkningar

**0** Indikerar att punkten är början på en figur.

**1** Indikerar att punkten är en av linjens två ändpunkter.

**3** Indikerar att punkten är en ändpunkt eller kontrollpunkt för en kubisk Bézier-spline.

**7** Maskerar alla bitar förutom de tre lägsta bitarna, som anger punkttypen.

**16** Anger att motsvarande segment är streckat.

**32** Anger att punkten är en markör.

**128** Anger att punkten är den sista punkten i en sluten underbana (figur).

**129** Indikerar en datapunkt som både är ett linjesegmentslut och den sista punkten i en sluten underbana.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ShapeElement](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)