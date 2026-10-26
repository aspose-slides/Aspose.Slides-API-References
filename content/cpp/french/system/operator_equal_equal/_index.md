---
title: operator==()
second_title: Référence API Aspose.Slides pour C++
description: 
type: docs
weight: 2016
url: /fr/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) fonction




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) fonction




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) fonction




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) fonction


Détermine si l'objet [Nullable](../nullable/) spécifié représente une valeur qui est égale à null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | std::nullptr_t | Une référence constante à un objet [Nullable](../nullable/) à tester |

### Valeur de retour

Vrai si l'objet spécifié représente une valeur null, faux sinon

## System::operator==(const T1\&, const Nullable\<T2\>\&) fonction


Détermine si la valeur spécifiée est égale à la valeur représentée par l'objet [Nullable](../nullable/) spécifié en appliquant [operator==()](./) à ces valeurs.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type de la première valeur comparande |
| T2 | Le type sous-jacent de l'objet [Nullable](../nullable/) qui représente la deuxième valeur comparande |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| some | const T1\& | Une référence constante à la valeur qui sera utilisée comme première comparande |
| other | const [Nullable](../nullable/)\<T2\>\& | Une référence constante à l'objet [Nullable](../nullable/) dont la valeur représentée sera utilisée comme deuxième comparande |

### Valeur de retour

Vrai si les comparandes sont égaux, sinon - faux

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) fonction


Compare l'égalité de deux pointeurs intelligents.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | Type pointé du premier pointeur. |
| Y | Type pointé du deuxième pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Premier pointeur à comparer. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Deuxième pointeur à comparer. |

### Valeur de retour

Vrai si les pointeurs correspondent, faux sinon.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) fonction


Vérifie si le pointeur intelligent est null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | Type pointé du pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | std::nullptr_t | Pointeur à vérifier. |

### Valeur de retour

Vrai si le pointeur est null, faux sinon.

## System::operator==(const SmartPtr\<X\>\&, const Y *) fonction


Comparaison d'égalité du pointeur intelligent avec un pointeur simple (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | type du pointeur intelligent. |
| Y | type du pointeur simple. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | pointeur intelligent à comparer (gauche). |
| y | const Y * | pointeur à comparer (droite). |

### Valeur de retour

Vrai si les pointeurs correspondent, faux sinon.

## System::operator==(const X *, const SmartPtr\<Y\>\&) fonction


Comparaison d'égalité du pointeur intelligent avec un pointeur simple (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | type du pointeur simple. |
| Y | type du pointeur intelligent. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const X * | pointeur à comparer (droite). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | pointeur intelligent à comparer (gauche). |

### Valeur de retour

Vrai si les pointeurs correspondent, faux sinon.

## System::operator==(T const\&, std::nullptr_t) fonction


Vérifie si l'objet de type valeur (structure C# traduite, etc.) est null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | T const\& | [Object](../object/) à vérifier. |

### Valeur de retour

Vrai si l'objet est null, faux sinon.

## System::operator==(std::nullptr_t, T const\&) fonction


Vérifie si l'objet de type valeur (structure C# traduite, etc.) est null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) à vérifier. |

### Valeur de retour

Vrai si l'objet est null, faux sinon.

## System::operator==(Chars\&, const String\&) fonction


[String](../string/) comparaison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Chars | Type littéral [String](../string/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | Chars\& | Littéral [String](../string/) à comparer. |
| right | const [String](../string/)\& | [String](../string/) à comparer. |

### Valeur de retour

vrai si les chaînes correspondent, faux sinon.

## System::operator==(T\&, const String\&) fonction


[String](../string/) comparaison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type pointeur [String](../string/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | T\& | pointeur [String](../string/) à comparer. |
| right | const [String](../string/)\& | [String](../string/) à comparer. |

### Valeur de retour

vrai si les chaînes correspondent, faux sinon.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) fonction


[Object](../object/) et comparaison de chaîne.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) à convertir en chaîne et comparer. |
| right | const [String](../string/)\& | [String](../string/) à comparer. |

### Valeur de retour

vrai si la représentation chaîne de l'objet est égale à la chaîne, faux sinon.

## System::operator==(std::nullptr_t, const String\&) fonction


Vérifie si la chaîne est null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) à vérifier. |

### Valeur de retour

vrai si la chaîne est null, faux sinon.

## System::operator==(std::nullptr_t, TimeSpan) fonction




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) fonction


Détermine si les URI représentés par les objets actuel et spécifié sont égaux.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Le premier objet [Uri](../uri/) à comparer |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Le deuxième objet [Uri](../uri/) à comparer |

### Valeur de retour

Vrai si les URI sont égaux, sinon - faux

## Voir aussi

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
* Structure [IsNullable](../isnullable/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)