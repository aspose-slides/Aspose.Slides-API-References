---
title: UnknownToObject()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte un tipo sconosciuto in Object, gestendo sia i tipi smart pointer sia i tipi valore.
type: docs
weight: 118
url: /it/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) metodo


Converte un tipo sconosciuto in [Object](../../object/), gestendo sia i tipi smart pointer sia i tipi valore.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo verso cui convertire [Object](../../object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T | [Object](../../object/) da convertire. |

### Valore restituito

Smart pointer a [Object](../../object/) che è sia il puntatore convertito sia il valore incapsulato.

## ObjectExt::UnknownToObject(const T&) metodo


Converte un tipo sconosciuto in [Object](../../object/), gestendo sia i tipi smart pointer sia i tipi valore.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo verso cui convertire [Object](../../object/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) da convertire. |

### Valore restituito

Smart pointer a [Object](../../object/) che è sia il puntatore convertito sia il valore incapsulato.

## Vedi anche

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)