---
title: Equals()
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 14
url: /it/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) metodo




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) metodo


Sostituzione per le chiamate C# [Object.Equals](../../object/equals/) che funzionano per qualsiasi tipo in C++. Sovraccarico per tipi di puntatore intelligente.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Primo tipo di oggetto. |
| T2 | Secondo tipo di oggetto. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | Primo oggetto. |
| another | const T2\& | Secondo oggetto. |

### Valore restituito

True se gli oggetti sono considerati uguali, false altrimenti.

## ObjectExt::Equals(T, const T2\&) metodo


Sostituzione per le chiamate C# [Object.Equals](../../object/equals/) che funzionano per qualsiasi tipo in C++. Sovraccarico per tipi di struttura.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Primo tipo di oggetto. |
| T2 | Secondo tipo di oggetto. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T | Primo oggetto. |
| another | const T2\& | Secondo oggetto. |

### Valore restituito

True se gli oggetti sono considerati uguali, false altrimenti.

## ObjectExt::Equals(const T\&, const T2\&) metodo


Sostituzione per le chiamate C# [Object.Equals](../../object/equals/) che funzionano per qualsiasi tipo in C++. Sovraccarico per tipi scalari.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Primo tipo di oggetto. |
| T2 | Secondo tipo di oggetto. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const T\& | Primo oggetto. |
| another | const T2\& | Secondo oggetto. |

### Valore restituito

True se gli oggetti sono considerati uguali, false altrimenti.

## ObjectExt::Equals(const char_t(&), String) metodo


Sostituzione per le chiamate C# [Object.Equals](../../object/equals/) che funzionano per qualsiasi tipo in C++. Sovraccarico per letterale stringa con confronto di stringhe.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| N | [String](../../string/) dimensione del letterale. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) letterale. |
| another | [String](../../string/) | [String](../../string/). |

### Valore restituito

True se le stringhe corrispondono, false altrimenti.

## ObjectExt::Equals(const float\&, const float\&) metodo


Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const **float**\& | Valore in virgola mobile LHS. |
| another | const **float**\& | Valore in virgola mobile RHS. |

### Valore restituito

True se **obj** e **another** sono entrambi NaN o uguali, false altrimenti.

## ObjectExt::Equals(const double\&, const double\&) metodo


Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const **double**\& | Valore in virgola mobile LHS. |
| another | const **double**\& | Valore in virgola mobile RHS. |

### Valore restituito

True se **obj** e **another** sono entrambi NaN o uguali, false altrimenti.

## Vedi anche

* Classe [ObjectExt](../)
* Classe [String](../../string/)
* Struttura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struttura [IsSmartPtr](../../issmartptr/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)