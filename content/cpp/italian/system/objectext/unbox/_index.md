---
title: Unbox()
second_title: Riferimento API di Aspose.Slides per C++
description: Estrae i tipi valore dopo la conversione a Object. Implementazione per i tipi enum.
type: docs
weight: 53
url: /it/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

Estrae i tipi valore dopo la conversione a [Object](../../object/). Implementazione per i tipi enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Enum](../../enum/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) da sbloccare. |

### Valore di ritorno

[Enum](../../enum/) valore.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

Estrae i tipi valore dopo la conversione a [Object](../../object/). Implementazione per tipi non enum e non nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) da sbloccare. |

### Valore di ritorno

Valore sbloccato.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

Estrae i tipi valore dopo la conversione a [Object](../../object/). Implementazione per tipi non enum e non nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) da sbloccare. |

### Valore di ritorno

Valore sbloccato.

## ObjectExt::Unbox(E) method

Estrae i tipi enum in intero.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo intero di destinazione. |
| E | Tipo enum di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| e | E | Valore da sbloccare. |

### Valore di ritorno

Rappresentazione intera dell'enum.

## ObjectExt::Unbox(E) method

Converte i tipi enum.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo enum di destinazione. |
| E | Tipo enum di origine. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| e | E | Valore da sbloccare. |

### Valore di ritorno

Valore enum convertito.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

Estrae i valori stringa.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) da sbloccare |

### Valore di ritorno

[String](../../string/) rappresentazione di stringa incapsulata, può essere null se la stringa incapsulata era null.

## Vedi anche

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Classe [String](../../string/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)