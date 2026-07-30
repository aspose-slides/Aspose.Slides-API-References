---
title: Equals()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se le due istanze IBaseSlide sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad esempio SlideId, e del contenuto dinamico, ad esempio il valore corrente della data nel Date Placeholder.
type: docs
weight: 183
url: /it/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) metodo

Determina se le due istanze [IBaseSlide](../) sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non prende in considerazione i valori degli identificatori unici, ad esempio SlideId, e il contenuto dinamico, ad esempio il valore della data corrente nel Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | Il [IBaseSlide](../) da confrontare con l'attuale [IBaseSlide](../). |

### Valore di ritorno

**true** se il [IBaseSlide](../) specificato è uguale all'attuale [IBaseSlide](../); altrimenti, **false**.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IBaseSlide](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)