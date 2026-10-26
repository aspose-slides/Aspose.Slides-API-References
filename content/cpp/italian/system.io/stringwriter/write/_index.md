---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive il carattere specificato sullo stream.
type: docs
weight: 40
url: /it/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) metodo

Scrive il carattere specificato sullo stream.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char_t | Il valore da scrivere |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodo

Scrive il sottointervallo specificato di caratteri dall'array di caratteri specificato sullo stream.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |
| index | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** al quale inizia il sottointervallo da scrivere |
| count | **int32_t** | Il numero di caratteri nel sottointervallo da scrivere |

## StringWriter::Write(const String\&) metodo

Scrive la stringa specificata sullo stream.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La stringa da scrivere |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* classe [StringWriter](../)
* classe [String](../../../system/string/)
* spazio dei nomi [System::IO](../../)
* libreria [Aspose.Slides](../../../)