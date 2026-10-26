---
title: get_substitutions method
second_title: Aspose.Slides Pythonhoz .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/fontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
Lekérdezi a prezentáció renderelésekor lecserélésre kerülő betűtípusok adatait.

### Visszatérési érték

Az összes betűtípuscsere gyűjteménye [`FontSubstitutionInfo`](/slides/python-net/hu/aspose.slides/fontsubstitutioninfo).



```python
def get_substitutions(self):
    ...
```



## get_substitutions(self, slides) {#listint}
Lekérdezi a megadott diák renderelése során lecserélésre kerülő betűtípusokkal kapcsolatos információkat.

### Visszatérési érték

Az összes betűtípuscsere ([`FontSubstitutionInfo`](/slides/python-net/hu/aspose.slides/fontsubstitutioninfo)) a megadott diákra vonatkozó gyűjteménye.



```python
def get_substitutions(self, slides):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| slides | **List[int]** | Egy tömb a diák indexeivel, amelyekhez a betűtípuscsere információját szeretnénk lekérni, 1-től kezdődően. |



### Lásd még
* osztály [`FontsManager`](/slides/python-net/hu/aspose.slides/fontsmanager)
* osztály [`FontSubstitutionInfo`](/slides/python-net/hu/aspose.slides/fontsubstitutioninfo)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)