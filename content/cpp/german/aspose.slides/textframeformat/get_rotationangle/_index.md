---
title: get_RotationAngle()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Wenn sie angegeben ist, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form eine Drehung erhalten kann, zusätzlich zu einer Drehung, die auf den Text selbst angewendet wird. Der resultierende Wert der visuellen Textdrehung wird aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammengefasst. Lies float.
type: docs
weight: 300
url: /de/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() Methode

Legt die benutzerdefinierte Drehung fest, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Falls sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Wird sie angegeben, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form eine Drehung erhalten kann, zusätzlich zu einer Drehung, die auf den Text selbst angewendet wird. Der resultierende Wert der visuellen Textdrehung wird aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammengefasst. Liest **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Anmerkungen

Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn aufgetragen wird. Zusätzlich dazu hat der Textkörper selbst eine Drehung von -90 Grad gegen den Uhrzeigersinn erhalten. Dann würde die resultierende Form gedreht erscheinen, während der Text darin so aussieht, als wäre er überhaupt nicht gedreht worden.

## Siehe auch

* Klasse [TextFrameFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)