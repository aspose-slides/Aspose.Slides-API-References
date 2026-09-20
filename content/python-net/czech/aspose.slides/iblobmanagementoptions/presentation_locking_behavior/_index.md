---
title: presentation_locking_behavior property
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior vlastnost
Tato vlastnost určuje, zda instance třídy Presentation může být vlastníkem zdroje – souboru
            nebo proudu během životnosti instance. Pokud je instance vlastníkem, uzamkne zdroj. To pomáhá
            zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor)
            nemůže být během životnosti instance Presentation změněn. Toto je příklad:

### Definice:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### Viz také
* třída [`IBlobManagementOptions`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)