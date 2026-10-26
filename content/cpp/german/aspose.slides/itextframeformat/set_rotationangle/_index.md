---
title: set_RotationAngle()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Wenn sie angegeben ist, wird diese unabhängig von der Form angewendet. Das bedeutet, dass die Form eine zusätzliche Drehung haben kann, während der Text selbst ebenfalls eine Drehung erhalten kann. Der resultierende visuelle Textdrehwert ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Schreiben Sie float.
type: docs
weight: 352
url: /de/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) Methode

Specifiziert die benutzerdefinierte Drehung, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Wenn sie angegeben ist, wird diese unabhängig von der Form angewendet. Das bedeutet, dass die Form eine zusätzliche Drehung besitzen kann, während der Text selbst ebenfalls eine Drehung erhalten kann. Der resultierende visuelle Textdrehwert ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Schreiben Sie **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Anmerkungen

Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn zugewiesen wird. Zusätzlich dazu ist der Textkörper selbst um -90 Grad gegen den Uhrzeigersinn gedreht. Das resultierende Ergebnis ist, dass die Form gedreht erscheint, der Text darin jedoch wirkt, als wäre er überhaupt nicht gedreht worden.

## Siehe auch

* Klasse [ITextFrameFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)