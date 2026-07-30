---
title: operator!=()
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 2055
url: /it/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) funzione




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) funzione




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) funzione




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) funzione


Determina se l'oggetto [Nullable](../nullable/) specificato rappresenta un valore non nullo.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | std::nullptr_t | Un riferimento costante a un oggetto [Nullable](../nullable/) da testare |

### Valore di ritorno

True se l'oggetto specificato rappresenta un valore non nullo, false altrimenti

## System::operator!=(const T1\&, const Nullable\<T2\>\&) funzione


Determina se il valore specificato non è uguale al valore rappresentato dall'oggetto [Nullable](../nullable/) specificato applicando [operator!=()](./) a questi valori.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T1 | Il tipo del primo valore comparato |
| T2 | Il tipo sottostante dell'oggetto [Nullable](../nullable/) che rappresenta il secondo valore comparato |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| some | const T1\& | Un riferimento costante al valore da utilizzare come primo comparando |
| other | const [Nullable](../nullable/)\<T2\>\& | Un riferimento costante all'oggetto [Nullable](../nullable/) il cui valore rappresentato deve essere usato come secondo comparando |

### Valore di ritorno

True se i comparandi non sono uguali, altrimenti - false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) funzione


Confronta due smart pointer per disuguaglianza.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | Tipo dell'oggetto puntato del primo puntatore. |
| Y | Tipo dell'oggetto puntato del secondo puntatore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Primo puntatore da confrontare. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Secondo puntatore da confrontare. |

### Valore di ritorno

False se i puntatori coincidono, true altrimenti.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) funzione


Verifica se lo smart pointer non è nullo.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | Tipo dell'oggetto puntato del puntatore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Puntatore da verificare. |

### Valore di ritorno

False se il puntatore è nullo, true altrimenti.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) funzione


Verifica se lo smart pointer non è nullo.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | Tipo dell'oggetto puntato del puntatore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | std::nullptr_t | Puntatore da verificare. |

### Valore di ritorno

False se il puntatore è nullo, true altrimenti.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) funzione


Confronto di disuguaglianza tra smart pointer e puntatore (C) semplice.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | tipo di smart pointer. |
| Y | tipo di puntatore semplice. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | smart pointer da confrontare (sinistra). |
| y | const Y * | puntatore da confrontare (destra). |

### Valore di ritorno

False se i puntatori coincidono, true altrimenti.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) funzione


Confronto di disuguaglianza tra puntatore semplice (C) e smart pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| X | tipo di puntatore semplice. |
| Y | tipo di smart pointer. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const X * | puntatore da confrontare (destra). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | smart pointer da confrontare (sinistra). |

### Valore di ritorno

False se i puntatori coincidono, true altrimenti.

## System::operator!=(Chars\&, const String\&) funzione


[String](../string/) comparison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Chars | Tipo letterale [String](../string/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | Chars\& | Letterale [String](../string/) da confrontare. |
| right | const [String](../string/)\& | [String](../string/) da confrontare. |

### Valore di ritorno

false se le stringhe coincidono, true altrimenti.

## System::operator!=(T\&, const String\&) funzione


[String](../string/) comparison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo puntatore [String](../string/). |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | T\& | Puntatore [String](../string/) da confrontare. |
| right | const [String](../string/)\& | [String](../string/) da confrontare. |

### Valore di ritorno

false se le stringhe coincidono, true altrimenti.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) funzione


[Object](../object/) and string comparison.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) da convertire in stringa e confrontare. |
| right | const [String](../string/)\& | [String](../string/) da confrontare. |

### Valore di ritorno

false se la rappresentazione stringa dell'oggetto è uguale alla stringa, true altrimenti.

## System::operator!=(std::nullptr_t, const String\&) funzione


Verifica se la stringa è nulla.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) da verificare. |

### Valore di ritorno

false se la stringa è nulla, true altrimenti.

## System::operator!=(std::nullptr_t, TimeSpan) funzione




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) funzione


Determina se gli URI rappresentati dagli oggetti corrente e specificato non sono uguali.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Il primo oggetto [Uri](../uri/) da confrontare |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Il secondo oggetto [Uri](../uri/) da confrontare |

### Valore di ritorno

True se gli URI non sono uguali, altrimenti - false

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* Classe [ArraySegment](../arraysegment/)
* Classe [DateTime](../datetime/)
* Classe [DateTimeOffset](../datetimeoffset/)
* Classe [Nullable](../nullable/)
* Classe [SmartPtr](../smartptr/)
* Classe [Object](../object/)
* Classe [String](../string/)
* Classe [TimeSpan](../timespan/)
* Classe [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)