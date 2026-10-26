---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive il valore intero senza segno a 8-bit specificato nel flusso di output.
type: docs
weight: 92
url: /it/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) metodo

Scrive il valore intero senza segno a 8-bit specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint8_t** | Il valore da scrivere |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) metodo

Scrive l'intervallo specificato di byte dall'array di byte specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array contenente i byte da scrivere |
| index | int | Un indice basato su 0 dell'elemento in **buffer** in cui inizia l'intervallo da scrivere |
| count | int | Il numero di elementi nell'intervallo da scrivere; -1 indica che l'intervallo termina dove finisce l'array **buffer** |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) metodo

Scrive l'intervallo specificato di caratteri UTF-16 dall'array di caratteri specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |
| index | int | Un indice basato su 0 dell'elemento in **buffer** in cui inizia l'intervallo da scrivere |
| count | int | Il numero di caratteri nell'intervallo da scrivere; -1 indica che l'intervallo termina dove finisce l'array **buffer** |

## BinaryWriter::Write(bool) metodo

Scrive un byte singolo con valore 0 se **value** è 'true' e 1 se **value** è 'false' nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **bool** | Il valore booleano che specifica il valore del byte da scrivere nel flusso di output |

## BinaryWriter::Write(char16_t) metodo

Scrive il valore del carattere a 16-bit larghezza specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char16_t | Il valore da scrivere |

## BinaryWriter::Write(int16_t) metodo

Scrive il valore intero a 16-bit specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **int16_t** | Il valore da scrivere |

## BinaryWriter::Write(int) metodo

Scrive il valore intero a 32-bit specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | Il valore da scrivere |

## BinaryWriter::Write(int64_t) metodo

Scrive il valore intero a 64-bit specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **int64_t** | Il valore da scrivere |

## BinaryWriter::Write(uint16_t) metodo

Scrive il valore intero senza segno a 16-bit specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint16_t** | Il valore da scrivere |

## BinaryWriter::Write(uint32_t) metodo

Scrive il valore intero senza segno a 32-bit specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint32_t** | Il valore da scrivere |

## BinaryWriter::Write(uint64_t) metodo

Scrive il valore intero senza segno a 64-bit specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint64_t** | Il valore da scrivere |

## BinaryWriter::Write(float) metodo

Scrive il valore a precisione singola in virgola mobile specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **float** | Il valore da scrivere |

## BinaryWriter::Write(double) metodo

Scrive il valore a doppia precisione in virgola mobile specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Il valore da scrivere |

## BinaryWriter::Write(const Decimal\&) metodo

Scrive la rappresentazione in byte del valore [Decimal](../../../system/decimal/) specificato nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | Il valore da scrivere |

## BinaryWriter::Write(const String\&) metodo

Scrive una stringa con prefisso di lunghezza nella codifica corrente nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La stringa da scrivere |

## BinaryWriter::Write(const char_t *) metodo

Scrive una stringa con prefisso di lunghezza nella codifica corrente nel flusso di output.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da scrivere |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BinaryWriter](../)
* Classe [Decimal](../../../system/decimal/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)