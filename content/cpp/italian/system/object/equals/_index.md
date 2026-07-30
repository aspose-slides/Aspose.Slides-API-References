---
title: Equals()
second_title: Riferimento API Aspose.Slides per C++
description: Confronta gli oggetti usando la semantica C# Object.Equals.
type: docs
weight: 157
url: /it/system/object/equals/
---
## Object::Equals(ptr) metodo


Confronta oggetti usando la semantica C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) per confrontare quello corrente. |

### Valore di ritorno

True se gli oggetti sono considerati uguali e false altrimenti.

## Object::Equals(T1 const\&, T2 const\&) metodo


Confronta oggetti di tipo riferimento nello stile C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo del primo oggetto da confrontare. |
| T2 | Tipo del secondo oggetto da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objA | T1 const\& | Primo oggetto da confrontare. |
| objB | T2 const\& | Secondo oggetto da confrontare. |

### Valore di ritorno

True se gli oggetti corrispondono sia per riferimento sia per confronto semantico (tipo [Object.Equals](./)), false altrimenti.

## Object::Equals(T1 const\&, T2 const\&) metodo


Confronta oggetti di tipo valore nello stile C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T1 | Tipo del primo oggetto da confrontare. |
| T2 | Tipo del secondo oggetto da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objA | T1 const\& | Primo oggetto da confrontare. |
| objB | T2 const\& | Secondo oggetto da confrontare. |

### Valore di ritorno

True se gli oggetti sono considerati uguali mediante l'operatore di uguaglianza disponibile, false altrimenti.

## Object::Equals(float const\&, float const\&) metodo


Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, inclusi i NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objA | **float** const\& | Valore in virgola mobile a sinistra. |
| objB | **float** const\& | Valore in virgola mobile a destra. |

### Valore di ritorno

True se **objA** e **objB** sono entrambi NaN o uguali, false altrimenti.

## Object::Equals(double const\&, double const\&) metodo


Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, inclusi i NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objA | **double** const\& | Valore in virgola mobile a sinistra. |
| objB | **double** const\& | Valore in virgola mobile a destra. |

### Valore di ritorno

True se **objA** e **objB** sono entrambi NaN o uguali, false altrimenti.

## Vedi anche

* Typedef [ptr](../ptr/)
* Classe [Object](../)
* Struttura [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)