---
title: get_PathTypes()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un array di valori byte che specificano il tipo di ogni punto nel percorso dell'elemento.
type: docs
weight: 27
url: /it/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() metodo

Restituisce un array di valori byte che specificano il tipo di ogni punto nel percorso dell'elemento.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Osservazioni

**0** Indica che il punto è l'inizio di una figura.

**1** Indica che il punto è una delle due estremità di una linea.

**3** Indica che il punto è un'estremità o un punto di controllo di una spline Bézier cubica.

**7** Maschera tutti i bit tranne i tre bit di ordine inferiore, che indicano il tipo di punto.

**16** Specifica che il segmento corrispondente è tratteggiato.

**32** Specifica che il punto è un marcatore.

**128** Specifica che il punto è l'ultimo punto in un sottotracciato chiuso (figura).

**129** Indica un punto dati che è sia un'estremità di segmento di linea sia l'ultimo punto di un sottotracciato chiuso.

## Vedi anche

* Definizione di tipo [ArrayPtr](../../../system/arrayptr/)
* Classe [ShapeElement](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)