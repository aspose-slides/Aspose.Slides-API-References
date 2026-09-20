---
title: first_slice_angle property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartseries/first_slice_angle/
weight: 140
---
## first_slice_angle egenskap
Specificerar vinkeln för den första paj- eller donutsdiagrammets segment, 
            i grader (medurs från upp, från 0 till 360 grader).
            Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen 
            - detta är en projektion av den lämpliga gruppens egenskap. Således är denna egenskap 
            skrivskyddad.
            Använd ParentSeriesGroup egenskap för åtkomst till den överordnade serieggruppen.
            Använd ParentSeriesGroup.FirstSliceAngle läsa/skriva egenskap för att ändra värdet.
            Skrivskyddad **int**.

### Anmärkningar

Detta är projektionen av egenskapen ParentSeriesGroup.FirstSliceAngle.

### Definition:
```python
@property
def first_slice_angle(self):
    ...
```

### Se även
* klass [`IChartSeries`](/slides/python-net/sv/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)