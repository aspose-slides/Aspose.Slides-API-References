---
title: get_substitutions method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ifontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
Hämtar information om typsnitt som kommer att ersättas vid presentationens rendering.

### Returnerar
Samling av alla typsnittsersättningar [`FontSubstitutionInfo`](/slides/python-net/sv/aspose.slides/fontsubstitutioninfo).



```python
def get_substitutions(self):
    ...
```



## get_substitutions(self, slides) {#listint}
Hämtar information om typsnitt som kommer att ersättas under rendering av de angivna bilderna.

### Returnerar
En samling av alla typsnittsersättningar ([`FontSubstitutionInfo`](/slides/python-net/sv/aspose.slides/fontsubstitutioninfo)) för de angivna bilderna.



```python
def get_substitutions(self, slides):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| slides | **List[int]** | En array av bildindex för vilka typsnittsersättningsinformation ska hämtas, med start från 1. |



### Se också
* klass [`FontSubstitutionInfo`](/slides/python-net/sv/aspose.slides/fontsubstitutioninfo)
* klass [`IFontsManager`](/slides/python-net/sv/aspose.slides/ifontsmanager)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)