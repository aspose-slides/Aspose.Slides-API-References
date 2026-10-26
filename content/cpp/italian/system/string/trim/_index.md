---
title: Trim()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove tutti i caratteri di spazio bianco sia all'inizio che alla fine della stringa.
type: docs
weight: 677
url: /it/system/string/trim/
---
## String::Trim() const metodo


Rimuove tutti i caratteri di spazio bianco sia all'inizio che alla fine della stringa.

```cpp
String System::String::Trim() const
```


### Valore restituito

[String](../) senza spazi bianchi all'inizio o alla fine.

## String::Trim(char_t) const metodo


Rimuove tutte le occorrenze del carattere passato sia all'inizio che alla fine della stringa.

```cpp
String System::String::Trim(char_t ch) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ch | char_t | Simbolo da rimuovere. |

### Valore restituito

Risultato della rimozione.

## String::Trim(const String\&) const metodo


Rimuove tutte le occorrenze dei caratteri passati sia all'inizio che alla fine della stringa.

```cpp
String System::String::Trim(const String &anyOf) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) di caratteri da rimuovere. |

### Valore restituito

[String](../) senza i caratteri rimossi.

## String::Trim(const ArrayPtr\<char_t\>\&) const metodo


Rimuove tutte le occorrenze dei caratteri passati sia all'inizio che alla fine della stringa.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) di caratteri da rimuovere. |

### Valore restituito

[String](../) senza i caratteri rimossi.

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)