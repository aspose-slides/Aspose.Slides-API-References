---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive la rappresentazione testuale del valore bool specificato nello stream di output rappresentato dall'oggetto corrente.
type: docs
weight: 14
url: /it/system/consoleoutput/write/
---
## ConsoleOutput::Write(bool) metodo


Scrive la rappresentazione testuale del valore bool specificato nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(bool value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **bool** | Il valore da scrivere |

## ConsoleOutput::Write(const SharedPtr\<Object\>\&) metodo


Scrive la rappresentazione testuale dell'oggetto specificato nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(const SharedPtr<Object> &value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | L'oggetto da scrivere |

## ConsoleOutput::Write(char_t) metodo


Scrive il valore del carattere specificato nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(char_t value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char_t | Il valore da scrivere |

## ConsoleOutput::Write(Decimal) metodo


Scrive la rappresentazione testuale del valore [Decimal](../../decimal/) nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(Decimal value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | Il valore da scrivere |

## ConsoleOutput::Write(double) metodo


Scrive la rappresentazione testuale di un valore a virgola mobile a doppia precisione nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(double value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Il valore da scrivere |

## ConsoleOutput::Write(int32_t) metodo


Scrive la rappresentazione testuale di un valore intero a 32 bit nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(int32_t value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **int32_t** | Il valore da scrivere |

## ConsoleOutput::Write(int64_t) metodo


Scrive la rappresentazione testuale di un valore intero a 64 bit nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(int64_t value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **int64_t** | Il valore da scrivere |

## ConsoleOutput::Write(float) metodo


Scrive la rappresentazione testuale di un valore a virgola mobile a precisione singola nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(float value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **float** | Il valore da scrivere |

## ConsoleOutput::Write(const String\&) metodo


Scrive l'oggetto stringa specificato nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(const String &value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | L'oggetto stringa da scrivere |

## ConsoleOutput::Write(uint32_t) metodo


Scrive la rappresentazione testuale di un valore intero senza segno a 32 bit nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(uint32_t value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint32_t** | Il valore da scrivere |

## ConsoleOutput::Write(uint64_t) metodo


Scrive la rappresentazione testuale di un valore intero senza segno a 64 bit nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(uint64_t value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint64_t** | Il valore da scrivere |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&) metodo


Scrive la rappresentazione testuale dell'array di caratteri specificato nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | L'array da scrivere |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodo


Scrive la rappresentazione testuale di un intervallo di valori dell'array di caratteri specificato nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | L'array contenente i valori da scrivere |
| index | **int32_t** | L'indice a cui inizia l'intervallo di elementi da scrivere |
| count | **int32_t** | Il numero di elementi nell'intervallo di elementi da scrivere |

## ConsoleOutput::Write(const char_t *) metodo


Scrive la c-stringa specificata nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(const char_t *value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-stringa da scrivere |

## ConsoleOutput::Write(const TypeInfo\&) metodo


Scrive la rappresentazione testuale dell'oggetto [TypeInfo](../../typeinfo/) specificato nello stream di output rappresentato dall'oggetto corrente.

```cpp
void System::ConsoleOutput::Write(const TypeInfo &value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | L'oggetto [TypeInfo](../../typeinfo/) da scrivere |

## ConsoleOutput::Write(const char *) metodo




```cpp
void System::ConsoleOutput::Write(const char *)=delete
```

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [ConsoleOutput](../)
* Class [Object](../../object/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)