---
title: TrimStart()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove tutti i caratteri di spazio bianco dall'inizio della stringa.
type: docs
weight: 690
url: /it/system/string/trimstart/
---
## String::TrimStart() const metodo

Rimuove tutti i caratteri di spazio bianco dall'inizio della stringa.

```cpp
String System::String::TrimStart() const
```

### Valore di ritorno

[String](../) senza spazi bianchi all'inizio.

## String::TrimStart(char_t) const metodo

Rimuove tutte le occorrenze del carattere passato dall'inizio della stringa.

```cpp
String System::String::TrimStart(char_t ch) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ch | char_t | Simbolo da rimuovere. |

### Valore di ritorno

Risultato della rimozione.

## String::TrimStart(const String\&) const metodo

Rimuove tutte le occorrenze dei caratteri passati dall'inizio della stringa.

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) di caratteri da rimuovere. |

### Valore di ritorno

[String](../) senza i caratteri rimossi.

## String::TrimStart(const ArrayPtr\<char_t\>\&) const metodo

Rimuove tutte le occorrenze dei caratteri passati dall'inizio della stringa.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) di caratteri da rimuovere. |

### Valore di ritorno

[String](../) senza i caratteri rimossi.

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)