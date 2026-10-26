---
title: split_text_by_columns method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/textframe/split_text_by_columns/
weight: 60
---
## split_text_by_columns(self) {#}
Delar upp textinnehållet i [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe) till en array av strängar,  
            där varje element motsvarar en separat textkolumn i ramen.

### Returnerar

En array av strängar, där varje sträng representerar textinnehållet i en specifik kolumn  
            i [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe).



```python
def split_text_by_columns(self):
    ...
```


### Anmärkningar

Om textramen inte innehåller flera kolumner kommer den returnerade arrayen att ha ett enda element  
            som innehåller hela texten.  
            Tomma kolumner kommer att representeras som tomma strängar i arrayen.



### Se även
* klass [`ITextFrame`](/slides/python-net/sv/aspose.slides/itextframe)
* klass [`TextFrame`](/slides/python-net/sv/aspose.slides/textframe)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)