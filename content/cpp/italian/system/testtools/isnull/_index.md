---
title: IsNull()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se il valore specifico è nullo. Versione per tipi aritmetici ed enum.
type: docs
weight: 1
url: /it/system/testtools/isnull/
---
## TestTools::IsNull(T) metodo

Verifica se il valore specifico è nullo. [Version](../../version/) per tipi aritmetici ed enum.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del valore da verificare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T | Valore da verificare per null. |

### Valore di ritorno

Restituisce sempre false.

## TestTools::IsNull(const T\&) metodo

Verifica se il valore specifico è nullo. [Version](../../version/) per tipi non aritmetici e non enum.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del valore da verificare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | Valore da verificare per null. |

### Valore di ritorno

Vero se l'oggetto è confrontato con nullptr come vero, falso altrimenti.

## TestTools::IsNull(const SharedPtr\<T\>\&) metodo

Verifica se il valore specifico è nullo. [Version](../../version/) per tipi non aritmetici.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo del valore da verificare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | Valore da verificare per null. |

### Valore di ritorno

Vero se l'oggetto è confrontato con nullptr come vero, falso altrimenti.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) metodo

Verifica se il valore specifico è nullo. [Version](../../version/) per coppie chiave-valore.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| K | Tipo della chiave. |
| V | Tipo del valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Oggetto coppia. |

### Valore di ritorno

Vero se la coppia è considerata nulla, falso altrimenti.

## TestTools::IsNull(const System::String\&) metodo

Verifica se la stringa è nulla.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) da verificare. |

### Valore di ritorno

Vero se la stringa è considerata nulla, falso altrimenti.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Classe [String](../../string/)
* Struttura [TestTools](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)