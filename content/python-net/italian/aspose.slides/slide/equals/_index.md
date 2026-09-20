---
title: equals method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/slide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina se le due istanze di IBaseSlide sono uguali.  
Il valore restituito è calcolato in base alla struttura della slide e al contenuto statico.  
Due slide sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori di identificatori unici, ad es. SlideId, né del contenuto dinamico, ad es. il valore della data corrente nel segnaposto Data.

### Restituisce

**true** se l'IBaseSlide specificato è uguale all'IBaseSlide corrente;  
altrimenti, **false** .



```python
def equals(self, slide):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide) | L'IBaseSlide da confrontare con l'IBaseSlide corrente. |

### Vedi anche
* classe [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide)
* classe [`Slide`](/slides/python-net/it/aspose.slides/slide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)