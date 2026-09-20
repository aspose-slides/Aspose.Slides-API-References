---
title: equals method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/notesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determina se le due istanze di IBaseSlide sono uguali.
            Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico.
            Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad es. SlideId e del contenuto dinamico, ad es. il valore della data corrente nel segnaposto Data.

### Valore restituito

**true**  se l'IBaseSlide specificato è uguale all'IBaseSlide corrente; 
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
* classe [`NotesSlide`](/slides/python-net/it/aspose.slides/notesslide)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)