---
title: WriteLine()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive i caratteri di terminazione di riga sul flusso.
type: docs
weight: 92
url: /it/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() metodo

Scrive i caratteri di terminazione di riga sul flusso.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) metodo

Scrive la stringa specificata seguita dai caratteri di terminazione di riga sul flusso.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La stringa da scrivere |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) metodo

Scrive la rappresentazione in stringa dell'oggetto specificato seguita dai caratteri di terminazione di riga sul flusso.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | L'oggetto da scrivere |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) metodo

Scrive tutti i caratteri dall'array specificato seguiti dai caratteri di terminazione di riga sul flusso.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodo

Scrive l'intervallo specificato di caratteri UTF-16 dall'array di caratteri specificato, seguito dai caratteri di terminazione di riga sul flusso.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |
| index | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** al quale inizia l'intervallo da scrivere |
| count | **int32_t** | Il numero di caratteri nell'intervallo da scrivere; -1 specifica che l'intervallo termina dove termina l'array **buffer** |

## StreamWriter::WriteLine(const char_t *) metodo

Scrive la c-string specificata seguita dai caratteri di terminazione di riga sul flusso.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const char_t * | La c-string da scrivere |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) metodo

Scrive la rappresentazione in stringa dell'oggetto specificato seguita dai caratteri di terminazione di riga sul flusso.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'oggetto |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | L'oggetto da scrivere |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StreamWriter](../)
* Classe [String](../../../system/string/)
* Classe [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)