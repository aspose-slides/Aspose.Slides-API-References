---
title: AppendFormat()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge la stringa formattata al builder.
type: docs
weight: 131
url: /it/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) metodo


Aggiunge la stringa formattata al builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TArgs | Tipo degli argomenti. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Stringa di formato. |
| args | const TArgs\&... | Argomenti da inserire nelle posizioni della stringa di formato. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) metodo


Aggiunge la stringa formattata al builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TArgs | Tipo degli argomenti. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Provider di formato; ignorato. |
| format | const [String](../../../system/string/)\& | Stringa di formato. |
| args | const TArgs\&... | Argomenti da inserire nelle posizioni della stringa di formato. |

### Valore di ritorno

Questo puntatore.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [StringBuilder](../)
* Classe [String](../../../system/string/)
* Classe [IFormatProvider](../../../system/iformatprovider/)
* Spazio dei nomi [System::Text](../../)
* Libreria [Aspose.Slides](../../../)