---
title: Point class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.animation/point/
---
## Point Klasse

Stellt einen Animationspunkt dar.

Der Typ Point stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides.animation/point/__init__/#) | Standardkonstruktor. |
| [`__init__(self, time, value, formula)`](/slides/python-net/de/aspose.slides.animation/point/__init__/#float-any-str) | Erstellt einen Animationspunkt mit Zeit, Wert und Formel. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`time`](/slides/python-net/de/aspose.slides.animation/point/time/) | Stellt den Zeitwert dar.<br/>            Lesen/Schreiben **float**. |
| [`value`](/slides/python-net/de/aspose.slides.animation/point/value/) | Stellt den Punktwert dar.<br/>            Nur: bool, ColorFormat, float, int, string.<br/>            Lesen/Schreiben **any**. |
| [`formula`](/slides/python-net/de/aspose.slides.animation/point/formula/) | Formeln innerhalb von Werten, den Attributen from, to, by können aus folgenden Elementen bestehen:<br/>            Standard-Arithmetikoperatoren: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Konstanten: ‘pi’ ‘e’<br/>            Bedingungsoperatoren: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Vergleichsoperatoren: '==', '>=', '', '!=', '!'<br/>            Trigonometrische Operatoren: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Natürlicher Logarithmus ‘ln()’<br/>            Property-Referenzen (vom Host unterstützte Eigenschaften)<br/>            <br/>            zum Beispiel: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Lesen/Schreiben **str**. |

### Siehe auch
* Modul [`aspose.slides.animation`](/slides/python-net/de/aspose.slides.animation)
* Bibliothek [`Aspose.Slides`](/slides/python-net)