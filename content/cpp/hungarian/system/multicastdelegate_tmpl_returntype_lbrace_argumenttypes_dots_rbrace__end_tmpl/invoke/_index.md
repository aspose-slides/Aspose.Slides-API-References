---
title: invoke()
second_title: Aspose.Slides C++ API referencia
description: Meghívja az összes jelenleg a delegáltak gyűjteményében lévő delegáltat. A delegáltak a gyűjteményhez hozzáadásuk sorrendjében kerülnek meghívásra. A metódus blokkol, amíg a delegáltak végrehajtásra kerülnek.
type: docs
weight: 222
url: /hu/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const method


Meghívja az összes jelenleg a delegáltak gyűjteményében lévő delegáltat. A delegáltak a gyűjteménybe felvétel sorrendjében kerülnek meghívásra. A metódus blokkol, amíg a delegáltak végrehajtásra kerülnek.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | ArgumentTypes... | A delegáltak meghívásához átadandó argumentumok |

### Visszatérési érték

Az utolsó meghívott delegált visszatérési értéke

## Lásd még

* Osztály [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)