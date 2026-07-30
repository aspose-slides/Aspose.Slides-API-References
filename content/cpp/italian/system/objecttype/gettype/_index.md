---
title: GetType()
second_title: Riferimento API Aspose.Slides per C++
description: Implementa la traduzione di typeof(). Sovraccarico per puntatori intelligenti.
type: docs
weight: 1
url: /it/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) metodo


Implementa la traduzione di typeof(). Sovraccarico per puntatori intelligenti.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di oggetto puntatore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) per ottenere [TypeInfo](../../typeinfo/) per. |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive la classe finale dell'oggetto passato.

## ObjectType::GetType(const T\&) metodo


Implementa la traduzione di typeof(). Sovraccarico per strutture.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di struttura. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) per ottenere [TypeInfo](../../typeinfo/) per. |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive la classe finale dell'oggetto passato.

## ObjectType::GetType(const T\&) metodo


Implementa la traduzione di typeof(). Sovraccarico per eccezioni.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di eccezione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) per ottenere [TypeInfo](../../typeinfo/) per. |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive la classe finale dell'oggetto passato.

## ObjectType::GetType(const T) metodo


Implementa la traduzione di typeof(). Sovraccarico per tipi primitivi.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo primitivo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T | IGNORED |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive il tipo dell'oggetto passato.

## ObjectType::GetType(const T) metodo


Implementa la traduzione di typeof(). Sovraccarico per tipi [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Nullable](../../nullable/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T | IGNORED |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive il tipo dell'oggetto passato.

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per tipi primitivi.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo primitivo. |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive il tipo specificato.

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per tipi enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo primitivo. |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive il tipo specificato.

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per strutture e puntatori.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo primitivo. |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive la struttura specificata.

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo [Nullable](../../nullable/). |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive la struttura specificata.

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo MutlicastDelegate. |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive la struttura specificata.

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per strutture e puntatori.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo primitivo. |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive la struttura specificata o il tipo del puntato se richiesto per [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) metodo


Implementa la traduzione di typeof(). Sovraccarico per tipo stringa.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo primitivo. |

### Valore restituito

Riferimento costante alla struttura [TypeInfo](../../typeinfo/) che descrive il tipo [String](../../string/).

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metodo


Implementa la traduzione di typeof(). Sovraccarico per [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Vedi anche

* Classe [ObjectType](../)
* Classe [TypeInfo](../../typeinfo/)
* Classe [String](../../string/)
* Struttura [IsSmartPtr](../../issmartptr/)
* Struttura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struttura [IsNullable](../../isnullable/)
* Struttura [IsBoxable](../../isboxable/)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)