---
title: CalculateFormulas()
second_title: Aspose.Slides für C++ API Referenz
description: Berechnet alle Formeln in der Arbeitsmappe und aktualisiert die entsprechenden Zellwerte.
type: docs
weight: 14
url: /de/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() Methode

Berechnet alle Formeln in der Arbeitsmappe und aktualisiert die entsprechenden Zellwerte.

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## Hinweise

Das Beispiel zeigt, wie man einer Zelle eine Formel zuweist und einen Wert berechnet. Der Wert der Zelle \"B4\" wird auf 5 gesetzt.
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

## Siehe auch

* Klasse [IChartDataWorkbook](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)