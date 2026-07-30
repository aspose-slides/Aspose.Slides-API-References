---
title: Box()
second_title: Riferimento API di Aspose.Slides per C++
description: Confeziona i tipi valore per la conversione in Object. Implementazione per tipi enum.
type: docs
weight: 40
url: /it/system/objectext/box/
---
## ObjectExt::Box(const T\&) method

Confeziona i tipi valore per la conversione a [Object](../../object/). Implementazione per tipi enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Enum](../../enum/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) valore da confezionare. |

### Valore restituito

Puntatore intelligente a oggetto che conserva il valore confezionato.

## ObjectExt::Box(const T\&) method

Confeziona i tipi valore per la conversione a [Object](../../object/). Implementazione per tipi non enum.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | Valore da confezionare. |

### Valore restituito

Puntatore intelligente a oggetto che conserva il valore confezionato.

## ObjectExt::Box(const T\&) method

Confeziona i tipi [Nullable](../../nullable/) per la conversione a [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | Valore da confezionare. |

### Valore restituito

Puntatore intelligente a oggetto che conserva il valore confezionato.

## ObjectExt::Box(const String\&) method

Confeziona valori stringa.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | Valore da confezionare. |

### Valore restituito

Valore confezionato o null, se la stringa di origine è null.

## Vedi anche

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Classe [String](../../string/)
* Struttura [IsNullable](../../isnullable/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)