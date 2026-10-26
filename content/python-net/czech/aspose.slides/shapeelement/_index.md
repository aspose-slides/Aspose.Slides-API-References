---
title: ShapeElement class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapeelement/
---
## ShapeElement třída

Představuje část tvaru se stejnými vlastnostmi obrysu a výplně.

Typ ShapeElement poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`parent_shape`](/slides/python-net/cs/aspose.slides/shapeelement/parent_shape/) | Vrací Shape_PPT, pro který byl prvek vytvořen.<br/>            Pouze pro čtení [`Shape`](/slides/python-net/cs/aspose.slides/shape). |
| [`path_points`](/slides/python-net/cs/aspose.slides/shapeelement/path_points/) | Získá pole bodů, které definují geometrii cesty prvku. |
| [`path_types`](/slides/python-net/cs/aspose.slides/shapeelement/path_types/) | Získá pole hodnot typu byte, které určují typ každého bodu v cestě prvku. <br/>            <br/>**0**  Naznačuje, že bod je začátek útvaru.<br/><br/><br/>**1**  Naznačuje, že bod je jedním ze dvou koncových bodů čáry.<br/><br/><br/>**3**  Naznačuje, že bod je koncovým nebo řídicím bodem kubické Bézierovy křivky.<br/><br/><br/>**7**  Maskuje všechny bity kromě tří nejnižších bitů, které určují typ bodu.<br/><br/><br/>**16**  Určuje, že odpovídající úsek je přerušovaný.<br/><br/><br/>**32**  Určuje, že bod je značkou.<br/><br/><br/>**128**  Určuje, že bod je posledním bodem uzavřené podcesty (úryvek).<br/><br/><br/>**129**  Naznačuje datový bod, který je zároveň koncovým bodem úsečky a posledním bodem uzavřené podcesty. |
| [`fill_source`](/slides/python-net/cs/aspose.slides/shapeelement/fill_source/) | Vrací informace o tom, jak vyplnit prvek.<br/>            Pouze pro čtení [`ShapeElementFillSource`](/slides/python-net/cs/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/cs/aspose.slides/shapeelement/stroke_source/) | Vrací informace o tom, jak obtáhnout prvek.<br/>            Pouze pro čtení [`ShapeElementStrokeSource`](/slides/python-net/cs/aspose.slides/shapeelementstrokesource). |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)