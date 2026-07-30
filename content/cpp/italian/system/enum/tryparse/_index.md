---
title: TryParse()
second_title: Riferimento API Aspose.Slides per C++
description: Prova a convertire la stringa specificata nella costante enum equivalente.
type: docs
weight: 79
url: /it/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) metodo

Prova a convertire la stringa specificata nella costante enum equivalente.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) che viene interpretato come contenente il nome della costante enum |
| result | E\& | Il parametro di output che, se la conversione riesce, contiene il risultato della conversione sulla funzione |

### Valore di ritorno

True se la conversione è riuscita, altrimenti - false

## Enum::TryParse(const String\&, bool, E\&) metodo

Prova a convertire la stringa specificata nella costante enum equivalente.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) che viene interpretato come contenente il nome della costante enum |
| ignoreCase | **bool** | Specifica se il caso deve essere ignorato durante l'interpretazione della stringa |
| result | E\& | Il parametro di output che, se la conversione riesce, contiene il risultato della conversione sul valore di ritorno della funzione |

### Valore di ritorno

True se la conversione è riuscita, altrimenti - false

## Vedi anche

* Classe [String](../../string/)
* Struttura [Enum](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)