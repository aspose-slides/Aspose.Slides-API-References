---
title: operator!=()
second_title: Référence API Aspose.Slides pour C++
description: 
type: docs
weight: 2029
url: /fr/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) fonction




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) fonction




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) fonction




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) fonction


Détermine si l'objet [Nullable](../nullable/) spécifié représente une valeur qui n'est pas égale à null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | std::nullptr_t | Une référence constante à un objet [Nullable](../nullable/) à tester |

### Valeur de retour

True si l'objet spécifié représente une valeur non nulle, false sinon

## System::operator!=(const T1\&, const Nullable\<T2\>\&) fonction


Détermine si la valeur spécifiée n'est pas égale à la valeur représentée par l'objet [Nullable](../nullable/) spécifié en appliquant [operator!=()](./) à ces valeurs.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type de la première valeur comparée |
| T2 | Le type sous-jacent de l'objet [Nullable](../nullable/) qui représente la seconde valeur comparée |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| some | const T1\& | Une référence constante à la valeur qui sera utilisée comme première comparande |
| other | const [Nullable](../nullable/)\<T2\>\& | Une référence constante à l'objet [Nullable](../nullable/) dont la valeur représentée sera utilisée comme seconde comparande |

### Valeur de retour

True si les comparandes ne sont pas égales, sinon - false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) fonction


Compare l'inégalité de deux pointeurs intelligents.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | Type pointeur du premier pointeur. |
| Y | Type pointeur du second pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Premier pointeur à comparer. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Second pointeur à comparer. |

### Valeur de retour

False si les pointeurs correspondent, true sinon.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) fonction


Vérifie si le pointeur intelligent n'est pas nul.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | Type pointeur du pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Pointeur à vérifier. |

### Valeur de retour

False si le pointeur est nul, true sinon.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) fonction


Vérifie si le pointeur intelligent n'est pas nul.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | Type pointeur du pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | std::nullptr_t | Pointeur à vérifier. |

### Valeur de retour

False si le pointeur est nul, true sinon.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) fonction


Comparaison d'inégalité du pointeur intelligent avec un pointeur simple (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
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

False si les pointeurs correspondent, true sinon.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) fonction


Comparaison d'égalité du pointeur intelligent avec un pointeur simple (C).

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
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

False si les pointeurs correspondent, true sinon.

## System::operator!=(Chars\&, const String\&) fonction


[String](../string/) comparaison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Chars | type littéral [String](../string/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | Chars\& | littéral [String](../string/) à comparer. |
| right | const [String](../string/)\& | [String](../string/) à comparer. |

### Valeur de retour

false si les chaînes correspondent, true sinon.

## System::operator!=(T\&, const String\&) fonction


[String](../string/) comparaison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type pointeur [String](../string/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | T\& | pointeur [String](../string/) à comparer. |
| right | const [String](../string/)\& | [String](../string/) à comparer. |

### Valeur de retour

false si les chaînes correspondent, true sinon.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) fonction


[Object](../object/) et comparaison de chaîne.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) à convertir en chaîne et comparer. |
| right | const [String](../string/)\& | [String](../string/) à comparer. |

### Valeur de retour

false si la représentation chaîne de l'objet est égale à la chaîne, true sinon.

## System::operator!=(std::nullptr_t, const String\&) fonction


Vérifie si la chaîne est nulle.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) à vérifier. |

### Valeur de retour

false si la chaîne est nulle, true sinon.

## System::operator!=(std::nullptr_t, TimeSpan) fonction




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) fonction


Détermine si les URI représentés par les objets actuel et spécifié ne sont pas égaux.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Le premier objet [Uri](../uri/) à comparer |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Le second objet [Uri](../uri/) à comparer |

### Valeur de retour

True si les URI ne sont pas égaux, sinon - false

## See Also

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