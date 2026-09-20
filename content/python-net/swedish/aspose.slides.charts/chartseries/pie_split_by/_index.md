---
title: pie_split_by property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by egenskap
Anger hur man bestämmer vilka datapunkter som ligger i den andra pajen eller stapeln på ett pie-of-pie eller bar-of-pie diagram. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade seriesgruppen – detta är en projektion av den lämpliga gruppegenskapen. Således är denna egenskap skrivskyddad. Använd ParentSeriesGroup egenskap för åtkomst till den överordnade seriesgruppen. Använd ParentSeriesGroup.PieSplitBy läs/skriv egenskap för att ändra värdet. Skrivskyddad [`PieSplitType`](/slides/python-net/sv/aspose.slides.charts/piesplittype).

### Anmärkningar

1) Detta är projektionen av egenskapen ParentSeriesGroup.PieSplitBy.  
2) Om egenskapsvärdet är PieSplitType.Custom kan du definiera anpassad delningsinformation med ParentSeriesGroup.PieSplitCustomPoints egenskap.

### Definition:
```python
@property
def pie_split_by(self):
    ...
```

### Se också
* klass [`ChartSeries`](/slides/python-net/sv/aspose.slides.charts/chartseries)
* enumeration [`PieSplitType`](/slides/python-net/sv/aspose.slides.charts/piesplittype)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)