---
title: Compare()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta le stringhe. Non implementato.
type: docs
weight: 66
url: /it/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const metodo

Confronta le stringhe. Non implementato.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | stringa LHS. |
| string2 | const [String](../../../system/string/)\& | stringa RHS. |

### Valore di ritorno

Valore negativo se la stringa LHS precede quella RHS, zero se coincidono, valore positivo altrimenti.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const metodo

Confronta le stringhe. Sono supportate solo le modalità Ordinal e OrdinalIgnoreCase.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | stringa LHS. |
| b | const [String](../../../system/string/)\& | stringa RHS. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) tipo di confronto. |

### Valore di ritorno

Valore negativo se la stringa LHS precede quella RHS, zero se coincidono, valore positivo altrimenti.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const metodo

Confronta una sezione di una stringa con una sezione di una seconda stringa. Non implementato.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Prima stringa. |
| offset1 | int | Indice iniziale dei caratteri in **string1**. |
| length1 | int | Numero di caratteri in **string1** da confrontare. |
| string2 | const [String](../../../system/string/)\& | Seconda stringa. |
| offset2 | int | Indice iniziale dei caratteri in **string2**. |
| length2 | int | Numero di caratteri in **string2** da confrontare. |

### Valore di ritorno

Valore negativo se la sezione della prima stringa precede quella della seconda, zero se coincidono, valore positivo altrimenti.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const metodo

Confronta la sezione finale di una stringa con la sezione finale di una seconda stringa usando i metodi di confronto delle stringhe. Non implementato.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Prima stringa. |
| offset1 | int | Indice iniziale dei caratteri in **string1**. |
| string2 | const [String](../../../system/string/)\& | Seconda stringa. |
| offset2 | int | Indice iniziale dei caratteri in **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) opzioni di confronto. |

### Valore di ritorno

Valore negativo se la sezione della prima stringa precede quella della seconda, zero se coincidono, valore positivo altrimenti.

## CompareInfo::Compare(const String\&, int, const String\&, int) const metodo

Confronta la sezione finale di una stringa con la sezione finale di una seconda stringa. Non implementato.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Prima stringa. |
| offset1 | int | Indice iniziale dei caratteri in **string1**. |
| string2 | const [String](../../../system/string/)\& | Seconda stringa. |
| offset2 | int | Indice iniziale dei caratteri in **string2**. |

### Valore di ritorno

Valore negativo se la sezione della prima stringa precede quella della seconda, zero se coincidono, valore positivo altrimenti.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const metodo

Confronta una sezione di una stringa con una sezione di una seconda stringa usando i metodi di confronto delle stringhe. Non implementato.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Prima stringa. |
| offset1 | int | Indice iniziale dei caratteri in **string1**. |
| length1 | int | Numero di caratteri in **string1** da confrontare. |
| string2 | const [String](../../../system/string/)\& | Seconda stringa. |
| offset2 | int | Indice iniziale dei caratteri in **string2**. |
| length2 | int | Numero di caratteri in **string2** da confrontare. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) opzioni di confronto. |

### Valore di ritorno

Valore negativo se la sezione della prima stringa precede quella della seconda, zero se coincidono, valore positivo altrimenti.

## Vedi anche

* Enum [CompareOptions](../../compareoptions/)
* Classe [String](../../../system/string/)
* Classe [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Libreria [Aspose.Slides](../../../)