---
title: ShapeElement class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapeelement/
---
## ShapeElement classe

Rappresenta una parte della forma con le stesse proprietà di contorno e riempimento.

Il tipo ShapeElement espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/it/aspose.slides/shapeelement/parent_shape/) | Restituisce uno Shape_PPT per il quale è stato creato l'elemento.<br/>Solo lettura [`Shape`](/slides/python-net/it/aspose.slides/shape). |
| [`path_points`](/slides/python-net/it/aspose.slides/shapeelement/path_points/) | Ottiene un array di punti che definisce la geometria del percorso dell'elemento. |
| [`path_types`](/slides/python-net/it/aspose.slides/shapeelement/path_types/) | Ottiene un array di valori byte che specificano il tipo di ogni punto nel percorso dell'elemento.<br/><br/>**0** Indica che il punto è l'inizio di una figura.<br/><br/>**1** Indica che il punto è uno dei due estremi di una linea.<br/><br/>**3** Indica che il punto è un punto finale o di controllo di una spline Bezier cubica.<br/><br/>**7** Maschera tutti i bit tranne i tre bit di ordine più basso, che indicano il tipo di punto.<br/><br/>**16** Specifica che il segmento corrispondente è tratteggiato.<br/><br/>**32** Specifica che il punto è un marcatore.<br/><br/>**128** Specifica che il punto è l'ultimo punto in un sottopercorso chiuso (figura).<br/><br/>**129** Indica un punto dati che è sia l'estremità di un segmento lineare sia l'ultimo punto di un sottopercorso chiuso. |
| [`fill_source`](/slides/python-net/it/aspose.slides/shapeelement/fill_source/) | Restituisce informazioni su come riempire un elemento.<br/>Solo lettura [`ShapeElementFillSource`](/slides/python-net/it/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/it/aspose.slides/shapeelement/stroke_source/) | Restituisce informazioni su come delineare un elemento.<br/>Solo lettura [`ShapeElementStrokeSource`](/slides/python-net/it/aspose.slides/shapeelementstrokesource). |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)