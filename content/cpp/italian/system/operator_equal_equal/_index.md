---
title: operator==()
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 2042
url: /it/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) funzione




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) funzione




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) funzione




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) funzione


Determina se l'oggetto [Nullable](../nullable/) specificato rappresenta un valore uguale a null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | std::nullptr_t | Un riferimento costante a un oggetto [Nullable](../nullable/) da testare |

### Valore di ritorno

Vero se l'oggetto specificato rappresenta un valore null, falso altrimenti

## System::operator==(const T1\&, const Nullable\<T2\>\&) funzione


Determina se il valore specificato è uguale al valore rappresentato dall'oggetto [Nullable](../nullable/) specificato applicando [operator==()](./) a questi valori.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del primo valore da confrontare |
| T2 | Il tipo di base dell'oggetto [Nullable](../nullable/) che rappresenta il secondo valore da confrontare |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| some | const T1\& | Un riferimento costante al valore da usare come primo comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | Un riferimento costante all'oggetto [Nullable](../nullable/) il cui valore rappresentato deve essere usato come secondo comparando |

### Valore di ritorno

Vero se i comparandi sono uguali, altrimenti - falso

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) funzione


Confronta per uguaglianza due smart pointer.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | Tipo di puntato del primo puntatore. |
| Y | Tipo di puntato del secondo puntatore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Primo puntatore da confrontare. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Secondo puntatore da confrontare. |

### Valore di ritorno

Vero se i puntatori corrispondono, falso altrimenti.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) funzione


Verifica se lo smart pointer è null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | Tipo di puntato del puntatore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | std::nullptr_t | Puntatore da verificare. |

### Valore di ritorno

Vero se il puntatore è null, falso altrimenti.

## System::operator==(const SmartPtr\<X\>\&, const Y *) funzione


Confronto di uguaglianza tra smart pointer e puntatore semplice (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | Tipo dello smart pointer. |
| Y | Tipo del puntatore semplice. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | smart pointer da confrontare (sinistro). |
| y | const Y * | puntatore da confrontare (destro). |

### Valore di ritorno

Vero se i puntatori corrispondono, falso altrimenti.

## System::operator==(const X *, const SmartPtr\<Y\>\&) funzione


Confronto di uguaglianza tra smart pointer e puntatore semplice (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | Tipo del puntatore semplice. |
| Y | Tipo dello smart pointer. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const X * | puntatore da confrontare (destro). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | smart pointer da confrontare (sinistro). |

### Valore di ritorno

Vero se i puntatori corrispondono, falso altrimenti.

## System::operator==(T const\&, std::nullptr_t) funzione


Verifica se l'oggetto di tipo valore (struttura C# tradotta, ecc.) è null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | T const\& | [Object](../object/) da verificare. |

### Valore di ritorno

Vero se l'oggetto è null, falso altrimenti.

## System::operator==(std::nullptr_t, T const\&) funzione


Verifica se l'oggetto di tipo valore (struttura C# tradotta, ecc.) è null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo valore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) da verificare. |

### Valore di ritorno

Vero se l'oggetto è null, falso altrimenti.

## System::operator==(Chars\&, const String\&) funzione


[String](../string/) confronto.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Chars | Tipo di letterale [String](../string/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | Chars\& | letterale [String](../string/) da confrontare. |
| right | const [String](../string/)\& | [String](../string/) da confrontare. |

### Valore di ritorno

vero se le stringhe corrispondono, falso altrimenti.

## System::operator==(T\&, const String\&) funzione


[String](../string/) confronto.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo puntatore [String](../string/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | T\& | puntatore [String](../string/) da confrontare. |
| right | const [String](../string/)\& | [String](../string/) da confrontare. |

### Valore di ritorno

vero se le stringhe corrispondono, falso altrimenti.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) funzione


[Object](../object/) e confronto stringa.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) da convertire in stringa e confrontare. |
| right | const [String](../string/)\& | [String](../string/) da confrontare. |

### Valore di ritorno

vero se la rappresentazione a stringa dell'oggetto è uguale alla stringa, falso altrimenti.

## System::operator==(std::nullptr_t, const String\&) funzione


Verifica se la stringa è null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) da verificare. |

### Valore di ritorno

vero se la stringa è null, falso altrimenti.

## System::operator==(std::nullptr_t, TimeSpan) funzione




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) funzione


Determina se gli URI rappresentati dall'oggetto corrente e da quello specificato sono uguali.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Il primo [Uri](../uri/) oggetto da confrontare |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Il secondo [Uri](../uri/) oggetto da confrontare |

### Valore di ritorno

Vero se gli URI sono uguali, altrimenti - falso

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* classe [ArraySegment](../arraysegment/)
* classe [DateTime](../datetime/)
* classe [DateTimeOffset](../datetimeoffset/)
* classe [Nullable](../nullable/)
* classe [SmartPtr](../smartptr/)
* classe [Object](../object/)
* classe [String](../string/)
* classe [TimeSpan](../timespan/)
* classe [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* namespace [System](../)
* Library [Aspose.Slides](../../)