---
title: TrimEnd()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove tutti i caratteri di spaziatura dalla fine della stringa.
type: docs
weight: 703
url: /it/system/string/trimend/
---
## String::TrimEnd() const metodo

Rimuove tutti i caratteri di spaziatura dalla fine della stringa.

```cpp
String System::String::TrimEnd() const
```

### Valore restituito

[String](../) senza spazi bianchi all'inizio.

## String::TrimEnd(char_t) const metodo

Rimuove tutte le occorrenze del carattere fornito dalla fine della stringa.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | Simbolo da rimuovere. |

### Valore restituito

Risultato della rimozione.

## String::TrimEnd(const String\&) const metodo

Rimuove tutte le occorrenze dei caratteri forniti dalla fine della stringa.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) di caratteri da rimuovere. |

### Valore restituito

[String](../) senza i caratteri rimossi.

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const metodo

Rimuove tutte le occorrenze dei caratteri forniti dalla fine della stringa.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) di caratteri da rimuovere. |

### Valore restituito

[String](../) senza i caratteri rimossi.

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)