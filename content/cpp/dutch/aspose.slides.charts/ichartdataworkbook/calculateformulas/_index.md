---
title: CalculateFormulas()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent alle formules in de werkmap en werkt de bijbehorende celwaarden bij.
type: docs
weight: 14
url: /nl/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() methode


Berechnet alle formules in de werkmap en werkt de bijbehorende celwaarden bij.

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## Opmerkingen



Voorbeeld toont hoe een formule aan de cel toe te wijzen en een waarde te berekenen. De waarde van de \"B4\"-cel wordt ingesteld op 5. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## Zie ook

* Klasse [IChartDataWorkbook](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)