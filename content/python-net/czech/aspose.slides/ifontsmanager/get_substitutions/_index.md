---
title: get_substitutions method
second_title: Aspose.Slides pro Python přes .NET – referenční příručka API
description: 
type: docs
url: /cs/aspose.slides/ifontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
Získá informace o písmách, která budou nahrazena při vykreslování prezentace.

### Vrací
Kolekce všech substitucí písem [`FontSubstitutionInfo`](/slides/python-net/cs/aspose.slides/fontsubstitutioninfo).

```python
def get_substitutions(self):
    ...
```

## get_substitutions(self, slides) {#listint}
Získá informace o písmách, která budou nahrazena během vykreslování určených snímků.

### Vrací
Kolekce všech substitucí písem ([`FontSubstitutionInfo`](/slides/python-net/cs/aspose.slides/fontsubstitutioninfo)) pro zadané snímky.

```python
def get_substitutions(self, slides):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| slides | **List[int]** | Pole indexů snímků, pro které se mají načíst informace o substitucích písem, počínaje 1. |

### Viz také
* class [`FontSubstitutionInfo`](/slides/python-net/cs/aspose.slides/fontsubstitutioninfo)
* class [`IFontsManager`](/slides/python-net/cs/aspose.slides/ifontsmanager)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)