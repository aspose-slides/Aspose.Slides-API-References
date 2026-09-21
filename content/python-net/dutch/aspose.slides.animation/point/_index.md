---
title: Point class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.animation/point/
---
## Point klasse

Representeert animatiepunt.

Het Point-type maakt de volgende leden beschikbaar:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides.animation/point/__init__/#) | Standaardconstructor. |
| [`__init__(self, time, value, formula)`](/slides/python-net/nl/aspose.slides.animation/point/__init__/#float-any-str) | Maak animatiepunt met tijd, waarde en formule. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`time`](/slides/python-net/nl/aspose.slides.animation/point/time/) | Representeert tijdwaarde.<br/>            Lezen/schrijven **float**. |
| [`value`](/slides/python-net/nl/aspose.slides.animation/point/value/) | Representeert puntwaarde.<br/>            Only: bool, ColorFormat, float, int, string.<br/>            Lezen/schrijven **any**. |
| [`formula`](/slides/python-net/nl/aspose.slides.animation/point/formula/) | Formules binnen waarden, from, to, by attributen kunnen bestaan uit het volgende:<br/>            Standaard rekenkundige operatoren: ‘+’, ‘-’, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Constanten: ‘pi’ ‘e’<br/>            Conditionele operatoren: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Vergelijkingsoperatoren: '==', '>=', '', '!=', '!'<br/>            Trigonometrische operatoren: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Natuurlijke logaritme ‘ln()’<br/>            Eigenschapsreferenties (door host ondersteunde eigenschappen)<br/>            <br/>            bijvoorbeeld: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Lezen/schrijven **str**. |

### Zie ook
* module [`aspose.slides.animation`](/slides/python-net/nl/aspose.slides.animation)
* bibliotheek [`Aspose.Slides`](/slides/python-net)