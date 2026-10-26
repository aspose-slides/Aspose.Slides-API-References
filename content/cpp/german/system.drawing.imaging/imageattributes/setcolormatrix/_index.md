---
title: SetColorMatrix()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Farb-Anpassungsmatrix.
type: docs
weight: 183
url: /de/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) method

Setzt die Farb-Anpassungsmatrix.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorMatrix | const [SharedPtr](../../../system/sharedptr/)\<[ColorMatrix](../../colormatrix/)\>\& | Die zu setzende Farb-Anpassungsmatrix |
| mode | [ColorMatrixFlag](../../colormatrixflag/) | Gibt den Typ des Bildes und der Farbe an, die von der Farb-Anpassungsmatrix betroffen sein werden |
| type | [ColorAdjustType](../../coloradjusttype/) | Gibt den Typ der Objekte an, für die die Farb-Anpassungsmatrix festgelegt wird |

## Siehe auch

* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ColorMatrix](../../colormatrix/)
* Klasse [ImageAttributes](../)
* Namensraum [System::Drawing::Imaging](../../)
* Bibliothek [Aspose.Slides](../../../)