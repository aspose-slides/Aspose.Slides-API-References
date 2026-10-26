---
title: Point class
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.animation/point/
---
## classe Point

Rappresenta un punto di animazione.

Il tipo Point espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.animation/point/__init__/#) | Costruttore predefinito. |
| [`__init__(self, time, value, formula)`](/slides/python-net/it/aspose.slides.animation/point/__init__/#float-any-str) | Crea un punto di animazione con tempo, valore e formula. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`time`](/slides/python-net/it/aspose.slides.animation/point/time/) | Rappresenta il valore del tempo.<br/>            Lettura/scrittura **float**. |
| [`value`](/slides/python-net/it/aspose.slides.animation/point/value/) | Rappresenta il valore del punto.<br/>            Solo: bool, ColorFormat, float, int, string.<br/>            Lettura/scrittura **any**. |
| [`formula`](/slides/python-net/it/aspose.slides.animation/point/formula/) | Le formule all'interno di valori, attributi from, to, by possono essere composte da questi:<br/>            Operatori aritmetici standard: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Costanti: ‘pi’ ‘e’<br/>            Operatori condizionali: ‘abs’, ‘min’, ‘max’, ‘?’ (se)<br/>            Operatori di confronto: '==', '>=', '', '!=', '!'<br/>            Operatori trigonometrici: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logaritmo naturale ‘ln()’<br/>            Riferimenti a proprietà (proprietà supportate dall'host)<br/>            <br/>            ad esempio: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Lettura/scrittura **str**. |

### Vedi anche
* modulo [`aspose.slides.animation`](/slides/python-net/it/aspose.slides.animation)
* libreria [`Aspose.Slides`](/slides/python-net)