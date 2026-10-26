---
title: equals method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/baseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina se le due istanze di IBaseSlide sono uguali.
            Il valore restituito viene calcolato in base alla struttura della diapositiva e al contenuto statico.
            Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad esempio SlideId, né del contenuto dinamico, ad esempio il valore della data corrente nel segnaposto Data.

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
* classe [`BaseSlide`](/slides/python-net/it/aspose.slides/baseslide)
* classe [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)