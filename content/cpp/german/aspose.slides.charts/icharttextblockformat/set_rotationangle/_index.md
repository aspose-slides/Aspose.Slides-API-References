---
title: set_RotationAngle()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Wenn sie angegeben ist, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form eine Drehung erhalten kann, zusätzlich zu der Drehung, die auf den Text selbst angewendet wird. Der resultierende Wert der visuellen Textdrehung ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Schreiben Sie float.
type: docs
weight: 248
url: /de/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) Methode

Specifiziert die benutzerdefinierte Drehung, die auf den Text im Begrenzungsrahmen angewendet wird. Wenn sie nicht angegeben ist, wird die Drehung der zugehörigen Form verwendet. Wenn sie angegeben ist, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form eine Drehung erhalten kann, zusätzlich zu der Drehung, die auf den Text selbst angewendet wird. Der resultierende Wert der visuellen Textdrehung ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Schreiben **float**.

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## Anmerkungen

Betrachten Sie den Fall, dass einer Form eine Drehung von 90 Grad im Uhrzeigersinn zugewiesen wird. Zusätzlich wird auf den Textkörper selbst eine Drehung von -90 Grad gegen den Uhrzeigersinn angewendet. Dann würde die resultierende Form gedreht erscheinen, während der Text darin so wirkt, als wäre er überhaupt nicht gedreht worden.

## Siehe auch

* Klasse [IChartTextBlockFormat](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)