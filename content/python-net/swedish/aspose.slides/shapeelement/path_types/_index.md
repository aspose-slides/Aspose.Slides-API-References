---
title: path_types property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types egenskap
Hämtar en array av bytevärden som specificerar typen för varje punkt i elementets bana.

**0** Anger att punkten är början på en figur.

**1** Anger att punkten är en av de två ändpunkterna på en linje.

**3** Anger att punkten är en ändpunkt eller kontrollpunkt för en kubisk Bézier-spline.

**7** Maskerar alla bitar förutom de tre lägsta, vilka anger punkttypen.

**16** Anger att motsvarande segment är streckat.

**32** Anger att punkten är en markör.

**128** Anger att punkten är den sista punkten i en sluten underbana (figur).

**129** Anger en datapunkt som både är en linjesegmentslutpunkt och den sista punkten i en sluten underbana.

### Definition:
```python
@property
def path_types(self):
    ...
```

### Se även
* klass [`ShapeElement`](/slides/python-net/sv/aspose.slides/shapeelement)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)