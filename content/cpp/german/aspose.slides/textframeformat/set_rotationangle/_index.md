---
title: set_RotationAngle()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die benutzerdefinierte Drehung fest, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Wenn sie angegeben ist, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form eine Drehung haben kann, zusätzlich zu der Drehung, die der Text selbst erhält. Der resultierende Wert der visuellen Textdrehung wird aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammengefasst. Schreiben Sie float.
type: docs
weight: 313
url: /de/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) Methode

Legt die benutzerdefinierte Drehung fest, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Wenn sie angegeben ist, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form eine Drehung haben kann, zusätzlich dazu, dass der Text selbst eine Drehung erhalten hat. Der resultierende Wert der visuellen Textdrehung wird aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammengefasst. Schreiben **float**.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## Hinweise

Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn zugewiesen wurde. Zusätzlich dazu hat der Textkörper selbst eine Drehung von -90 Grad gegen den Uhrzeigersinn erhalten. Dann würde die resultierende Form zwar rotiert erscheinen, während der Text darin so wirkt, als wäre er überhaupt nicht rotiert worden.

## Siehe auch

* Klasse [TextFrameFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)