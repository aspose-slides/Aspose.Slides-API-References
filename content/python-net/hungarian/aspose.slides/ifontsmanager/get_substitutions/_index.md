---
title: get_substitutions method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/ifontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
Lekéri a betűtípusokról szóló információkat, amelyek a prezentáció megjelenítése során helyettesítésre kerülnek.

### Visszatérési érték
Az összes betűtípus-helyettesítés [`FontSubstitutionInfo`](/slides/python-net/hu/aspose.slides/fontsubstitutioninfo).



```python
def get_substitutions(self):
    ...
```



## get_substitutions(self, slides) {#listint}
Lekéri a betűtípusokról szóló információkat, amelyek a megadott diák megjelenítése során helyettesítésre kerülnek.

### Visszatérési érték
Az összes betűtípus-helyettesítés ([`FontSubstitutionInfo`](/slides/python-net/hu/aspose.slides/fontsubstitutioninfo)) gyűjteménye a megadott diákhoz.



```python
def get_substitutions(self, slides):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| slides | **List[int]** | A diák indexeinek tömbje, amelyekre a betűtípus-helyettesítési információkat le kell kérni, az 1-től kezdődően. |



### Lásd még
* class [`FontSubstitutionInfo`](/slides/python-net/hu/aspose.slides/fontsubstitutioninfo)
* class [`IFontsManager`](/slides/python-net/hu/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)