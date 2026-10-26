---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la rappresentazione stringa dell'oggetto specificato sul flusso di output standard.
type: docs
weight: 1
url: /it/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) metodo

Restituisce la rappresentazione stringa dell'oggetto specificato sul flusso di output standard.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo dell'oggetto da stampare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) da stampare |

## Console::Write(bool) metodo

Restituisce la rappresentazione stringa del valore bool sul flusso di output standard.

```cpp
static void System::Console::Write(bool value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **bool** | Il valore da stampare |

## Console::Write(char_t) metodo

Restituisce la rappresentazione stringa del valore carattere specificato sul flusso di output standard.

```cpp
static void System::Console::Write(char_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char_t | Il valore da stampare |

## Console::Write(const ArrayPtr\<char_t\>\&) metodo

Restituisce la rappresentazione stringa dell'array di caratteri specificato sul flusso di output standard.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | L'array da stampare |

## Console::Write(const Decimal\&) metodo

Restituisce la rappresentazione stringa del valore [Decimal](../../decimal/) sul flusso di output standard.

```cpp
static void System::Console::Write(const Decimal &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Il valore da stampare |

## Console::Write(double) metodo

Restituisce la rappresentazione stringa del valore a virgola mobile double sul flusso di output standard.

```cpp
static void System::Console::Write(double value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Il valore da stampare |

## Console::Write(float) metodo

Restituisce la rappresentazione stringa del valore a virgola mobile float sul flusso di output standard.

```cpp
static void System::Console::Write(float value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **float** | Il valore da stampare |

## Console::Write(int32_t) metodo

Restituisce la rappresentazione stringa del valore intero a 32 bit sul flusso di output standard.

```cpp
static void System::Console::Write(int32_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **int32_t** | Il valore da stampare |

## Console::Write(int64_t) metodo

Restituisce la rappresentazione stringa del valore intero a 64 bit sul flusso di output standard.

```cpp
static void System::Console::Write(int64_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **int64_t** | Il valore da stampare |

## Console::Write(const String\&) metodo

Restituisce la rappresentazione stringa dell'oggetto stringa specificato sul flusso di output standard.

```cpp
static void System::Console::Write(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | L'oggetto stringa da stampare |

## Console::Write(const char_t *) metodo

Restituisce la rappresentazione stringa della c-string specificata sul flusso di output standard.

```cpp
static void System::Console::Write(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da stampare |

## Console::Write(const TypeInfo\&) metodo

Restituisce la rappresentazione stringa del valore [TypeInfo](../../typeinfo/) sul flusso di output standard.

```cpp
static void System::Console::Write(const TypeInfo &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Il valore da stampare |

## Console::Write(uint32_t) metodo

Restituisce la rappresentazione stringa del valore intero senza segno a 32 bit sul flusso di output standard.

```cpp
static void System::Console::Write(uint32_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint32_t** | Il valore da stampare |

## Console::Write(uint64_t) metodo

Restituisce la rappresentazione stringa del valore intero senza segno a 64 bit sul flusso di output standard.

```cpp
static void System::Console::Write(uint64_t value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint64_t** | Il valore da stampare |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodo

Restituisce la rappresentazione stringa dell'intervallo specificato dell'array di caratteri specificato sul flusso di output standard.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | L'array di caratteri |
| index | **int32_t** | L'indice nell'array in cui inizia l'intervallo da stampare |
| count | **int32_t** | Il numero di elementi nell'intervallo da stampare |

## Console::Write(const String\&, Args\&&...) metodo

Restituisce la rappresentazione stringa degli argomenti specificati formattati secondo il formato specificato sul flusso di output standard.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| I | tipi dei valori da stampare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../../string/)\& | Il formato stringa |
| args | Args\&&... | I valori da stampare |

## Console::Write(const char *) metodo




```cpp
static void System::Console::Write(const char *)=delete
```

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Classe [Console](../)
* Classe [Decimal](../../decimal/)
* Classe [String](../../string/)
* Classe [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)