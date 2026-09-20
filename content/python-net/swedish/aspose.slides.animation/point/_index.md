---
title: Point class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.animation/point/
---
## Point klass

Representerar animeringspunkt.

Typen Point exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.animation/point/__init__/#) | Standardkonstruktor. |
| [`__init__(self, time, value, formula)`](/slides/python-net/sv/aspose.slides.animation/point/__init__/#float-any-str) | Skapa animationspunkt med tid, värde och formel. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`time`](/slides/python-net/sv/aspose.slides.animation/point/time/) | Representerar tidsvärde.<br/>            Läs/skriv **float**. |
| [`value`](/slides/python-net/sv/aspose.slides.animation/point/value/) | Representerar punktvärde.<br/>            Endast: bool, ColorFormat, float, int, string.<br/>            Läs/skriv **any**. |
| [`formula`](/slides/python-net/sv/aspose.slides.animation/point/formula/) | Formler inom värden, från, till, med attribut kan bestå av följande:<br/>            Standard aritmetiska operatorer: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Konstanter: ‘pi’ ‘e’<br/>            Villkorsoperatorer: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Jämförelseoperatorer: '==', '>=', '', '!=', '!'<br/>            Trigonometriska operatorer: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Naturlig logaritm ‘ln()’<br/>            Egendomsreferenser (värdstödda egenskaper)<br/>            <br/>            till exempel: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Läs/skriv **str**. |

### Se även
* modul [`aspose.slides.animation`](/slides/python-net/sv/aspose.slides.animation)
* bibliotek [`Aspose.Slides`](/slides/python-net)