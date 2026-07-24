---
title: get_RotationAngle()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die benutzerdefinierte Rotation fest, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Rotation der zugehörigen Form verwendet. Wenn sie angegeben ist, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form zusätzlich zu dem Text ebenfalls eine Rotation erhalten kann. Der resultierende Wert der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Lesen Sie float.
type: docs
weight: 339
url: /de/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() Methode

Legt die benutzerdefinierte Rotation fest, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Rotation der zugehörigen Form verwendet. Wenn sie angegeben ist, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form zusätzlich zu dem Text eine Rotation erhalten kann. Der resultierende Wert der visuellen Textrotation ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Lesen Sie **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## Anmerkungen

Betrachten Sie den Fall, dass eine Form eine um 90 Grad im Uhrzeigersinn angewandte Rotation aufweist. Zusätzlich dazu hat der Textkörper selbst eine um -90 Grad gegen den Uhrzeigersinn angewandte Rotation. Dann würde die resultierende Form rotiert erscheinen, während der Text darin so aussieht, als wäre er überhaupt nicht rotiert worden.

## Siehe auch

* Klasse [ITextFrameFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)