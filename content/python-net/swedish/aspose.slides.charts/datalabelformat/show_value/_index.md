---
title: show_value property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value egenskap
Representerar ett angivet diagramdatas etikettens procentsatsvisningsbeteende. 
            True visar procentsatsen. False för att dölja.
            Läs/skriv **bool**.


### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av datamarken, så hämtar eller anger detta egenskap standardvärdet för ShowValue-egenskapen för de nya datamärkena i DataLabelCollection-samlingen. Att sätta detta egenskap med ett värde sätter också detta värde till ShowValue-egenskapen för alla datamärken i DataLabelCollection-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" gör att alla DataLabels[i].ShowValue är lika med val).

### Definition:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### Se även
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)