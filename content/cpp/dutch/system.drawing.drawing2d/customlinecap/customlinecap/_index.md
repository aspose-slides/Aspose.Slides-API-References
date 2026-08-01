---
title: CustomLineCap()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de CustomLineCap-klasse die een door de gebruiker gedefinieerde lijnkap vertegenwoordigt met de opgegeven eigenschappen.
type: docs
weight: 1
url: /nl/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) constructor

Construeert een nieuw exemplaar van de [CustomLineCap](../) klasse die een door de gebruiker gedefinieerde lijnkap vertegenwoordigt met de opgegeven eigenschappen.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Specificeert een vulling voor de aangepaste kap |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Specificeert een omtrek van de aangepaste kap |
| baseCap | [LineCap](../../linecap/) | De basislijnkap waaruit de aangepaste kap wordt gemaakt |
| baseInset | **float** | Specificeert de afstand tussen de lijn en de kap |

## Zie ook

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [GraphicsPath](../../graphicspath/)
* Klasse [CustomLineCap](../)
* Naamruimte [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)