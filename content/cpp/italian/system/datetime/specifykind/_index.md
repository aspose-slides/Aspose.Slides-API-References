---
title: SpecifyKind()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un nuovo oggetto DateTime che rappresenta lo stesso numero di tick dell'oggetto DateTime specificato e rappresenta l'ora locale, l'ora UTC o nessuna delle due come specificato dall'argomento kind.
type: docs
weight: 833
url: /it/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) metodo

Crea un nuovo oggetto [DateTime](../) che rappresenta lo stesso numero di tick dell'oggetto [DateTime](../) specificato e rappresenta l'ora locale, l'ora UTC o nessuna delle due come specificato dall'argomento **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DateTime](../) | L'oggetto [DateTime](../) da cui copiare il numero di tick |
| kind | [DateTimeKind](../../datetimekind/) | Specifica se il nuovo oggetto deve rappresentare l'ora locale, l'ora UTC o nessuna delle due. |

### Valore restituito

Un nuovo oggetto [DateTime](../) che rappresenta lo stesso numero di tick di **value** e il valore DateTimeKind specificato da **kind**.

## Vedi anche

* Enumerazione [DateTimeKind](../../datetimekind/)
* Classe [DateTime](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)