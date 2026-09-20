---
title: IPoint class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.animation/ipoint/
---
## IPoint classe

Rappresenta un punto di animazione.

Il tipo IPoint espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`time`](/slides/python-net/it/aspose.slides.animation/ipoint/time/) | Rappresenta il valore di tempo.<br/>            Lettura/scrittura **float**. |
| [`value`](/slides/python-net/it/aspose.slides.animation/ipoint/value/) | Rappresenta il valore del punto.<br/>            Solo: bool, ColorFormat, float, int, string.<br/>            Lettura/scrittura **any**. |
| [`formula`](/slides/python-net/it/aspose.slides.animation/ipoint/formula/) | Le formule nei valori, negli attributi from, to, by, possono essere composte da questi:<br/>            Operatori aritmetici standard: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Costanti: ‘pi’ ‘e’<br/>            Operatori condizionali: ‘abs’, ‘min’, ‘max’, ‘?’ (se)<br/>            Operatori di confronto: '==', '>=', '', '!=', '!'<br/>            Operatori trigonometrici: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logaritmo naturale ‘ln()’<br/>            Riferimenti a proprietà (proprietà supportate dall'host)<br/>            <br/>            ad esempio: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Lettura/scrittura **str**. |


### Vedi anche
* modulo [`aspose.slides.animation`](/slides/python-net/it/aspose.slides.animation)
* libreria [`Aspose.Slides`](/slides/python-net)