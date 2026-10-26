---
title: ReferenceEquals()
second_title: Riferimento API di Aspose.Slides per C++
description: "Specializzazione di Object::ReferenceEquals per il caso di stringa e nullptr."
type: docs
weight: 261
url: /it/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) metodo

Specializzazione di [Object::ReferenceEquals](./) per il caso di stringa e nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) da confrontare con nullptr. |

### Valore di ritorno

true se la stringa è null, false altrimenti.

## Object::ReferenceEquals(String const\&, String const\&) metodo

Specializzazione di [Object::ReferenceEquals](./) per il caso di stringhe.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Prima stringa da confrontare. |
| str2 | [String](../../string/) const\& | Seconda stringa da confrontare. |

### Valore di ritorno

true se le stringhe corrispondono, false altrimenti.

## Object::ReferenceEquals(ptr const\&, ptr const\&) metodo

Confronta gli oggetti per riferimento.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Primo puntatore da confrontare. |
| objB | [ptr](../ptr/) const\& | Secondo puntatore da confrontare. |

### Valore di ritorno

True se i puntatori corrispondono e false altrimenti.

## Object::ReferenceEquals(T const\&, T const\&) metodo

Confronta gli oggetti per riferimento.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo degli oggetti da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objA | T const\& | Primo oggetto da confrontare. |
| objB | T const\& | Secondo oggetto da confrontare. |

### Valore di ritorno

True se gli indirizzi degli oggetti corrispondono e false altrimenti.

## Object::ReferenceEquals(T const\&, std::nullptr_t) metodo

Confronta per riferimento un oggetto di tipo valore con nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo dell'oggetto da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objA | T const\& | Primo oggetto da confrontare. |

### Valore di ritorno

Restituisce sempre false poiché i tipi valore non possono essere nulli.

## Vedi anche

* Typedef [ptr](../ptr/)
* Classe [String](../../string/)
* Classe [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)