---
title: operator+()
second_title: Riferimento API di Aspose.Slides per C++
description: Operatore di concatenazione di stringhe.
type: docs
weight: 274
url: /it/system/string/operator_plus/
---
## String::operator+(const String\&) const metodo

[String](../) operatore di concatenazione.

```cpp
String System::String::operator+(const String &str) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) da aggiungere alla fine di quello corrente. |

### Valore restituito

Stringa concatenata.

## String::operator+(const T\&) const metodo

[String](../) concatenazione con stringa letterale o puntatore a stringa di caratteri.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Una delle forme di stringa letterale o puntatore a stringa di caratteri. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg | const T\& | Entità da concatenare con la stringa corrente. |

### Valore restituito

Stringa concatenata.

## String::operator+(char_t) const metodo

Aggiunge un carattere alla fine della stringa.

```cpp
String System::String::operator+(char_t x) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | char_t | Carattere da aggiungere. |

### Valore restituito

[String](../) risultato della concatenazione.

## String::operator+(int) const metodo

Aggiunge la rappresentazione testuale di un valore intero alla fine della stringa.

```cpp
String System::String::operator+(int i) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | int | Valore intero da convertire in stringa e aggiungere. |

### Valore restituito

[String](../) risultato della concatenazione.

## String::operator+(uint32_t) const metodo

Aggiunge la rappresentazione testuale di un valore intero senza segno alla fine della stringa.

```cpp
String System::String::operator+(uint32_t i) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | **uint32_t** | Valore da convertire in stringa e aggiungere. |

### Valore restituito

[String](../) risultato della concatenazione.

## String::operator+(double) const metodo

Aggiunge la rappresentazione testuale di un valore a virgola mobile alla fine della stringa.

```cpp
String System::String::operator+(double d) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| d | **double** | Valore da convertire in stringa e aggiungere. |

### Valore restituito

[String](../) risultato della concatenazione.

## String::operator+(int64_t) const metodo

Aggiunge la rappresentazione testuale di un valore intero alla fine della stringa.

```cpp
String System::String::operator+(int64_t v) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | **int64_t** | Valore da convertire in stringa e aggiungere. |

### Valore restituito

[String](../) risultato della concatenazione.

## String::operator+(const T\&) const metodo

Aggiunge la rappresentazione testuale di un oggetto di tipo riferimento alla fine della stringa.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | tipo puntatore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) da convertire in stringa usando la chiamata [ToString()](../tostring/) e aggiungere alla stringa corrente. |

### Valore restituito

[String](../) risultato della concatenazione.

## String::operator+(const T\&) const metodo

Aggiunge la rappresentazione testuale di un oggetto di tipo valore alla fine della stringa.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo valore su cui chiamare [ToString()](../tostring/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) da convertire in stringa usando la chiamata [ToString()](../tostring/) e aggiungere alla stringa corrente. |

### Valore restituito

[String](../) risultato della concatenazione.

## String::operator+(T) const metodo

Aggiunge la rappresentazione testuale di un valore booleano alla fine della stringa.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo valore da concatenare con la stringa. Deve essere bool |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) valore da convertire in stringa e aggiungere. |

### Valore restituito

[String](../) risultato della concatenazione.

## Vedi anche

* Classe [String](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)