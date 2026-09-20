---
title: path_types property
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapeelement/path_types/
weight: 40
---
## path_types vlastnost
Získá pole bajtových hodnot, které určují typ každého bodu v cestě prvku. 
            
**0**  Ukazuje, že bod je začátek figury.


**1**  Ukazuje, že bod je jedním ze dvou koncových bodů čáry.


**3**  Ukazuje, že bod je koncovým bodem nebo řídicím bodem kubické Bézierovy křivky.


**7**  Maskuje všechny bity kromě tří nejnižších, které určují typ bodu.


**16**  Určuje, že odpovídající úsek je čárkovaný.


**32**  Určuje, že bod je značkou.


**128**  Určuje, že bod je posledním bodem v uzavřené podcestě (figuře).


**129**  Ukazuje datový bod, který je jak koncovým bodem úseku čáry, tak posledním bodem uzavřené podcesty.

### Definice:
```python
@property
def path_types(self):
    ...
```


### Viz také
* třída [`ShapeElement`](/slides/python-net/cs/aspose.slides/shapeelement)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)