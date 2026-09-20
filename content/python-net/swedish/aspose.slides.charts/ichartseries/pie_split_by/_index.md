---
title: pie_split_by property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by egenskap
Anger hur man bestämmer vilka datapunkter som ingår i den andra pajen eller stapeln 
            på ett pie-of-pie- eller bar-of-pie-diagram.
            Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade seriegrouppen 
            - detta är en projicering av den lämpliga gruppegenskapen. Och därför är denna egenskap 
            skrivskyddad.
            Använd ParentSeriesGroup-egenskapen för åtkomst till den överordnade seriegrouppen.
            Använd ParentSeriesGroup.PieSplitBy läs/skriv egenskap för att ändra värdet.
            Skrivskyddad [`PieSplitType`](/slides/python-net/sv/aspose.slides.charts/piesplittype).


### Anmärkningar

1) Detta är projiceringen av egenskapen ParentSeriesGroup.PieSplitBy.
            2) Om egenskapsvärdet är PieSplitType.Custom kan du definiera anpassad delningsinformation 
            med ParentSeriesGroup.PieSplitCustomPoints-egenskapen.

### Definition:
```python
@property
def pie_split_by(self):
    ...
```


### Se även
* klass [`IChartSeries`](/slides/python-net/sv/aspose.slides.charts/ichartseries)
* enumeration [`PieSplitType`](/slides/python-net/sv/aspose.slides.charts/piesplittype)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)