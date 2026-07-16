---
title: operator+()
second_title: Référence API Aspose.Slides pour C++
description: Opérateur de concaténation de chaînes.
type: docs
weight: 274
url: /fr/system/string/operator_plus/
---
## String::operator+(const String\&) const method


[String](../) opérateur de concaténation.

```cpp
String System::String::operator+(const String &str) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) à ajouter à la fin du texte actuel. |

### Return Value

Valeur de retour  
Chaîne concaténée.

## String::operator+(const T\&) const method


[String](../) concaténation avec littéral de chaîne ou pointeur de chaîne de caractères.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### Template parameters

| Paramètre | Description |
| --- | --- |
| T | L'une des formes de littéral de chaîne ou de pointeur de chaîne de caractères. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arg | const T\& | Entité à concaténer avec la chaîne actuelle. |

### Return Value

Valeur de retour  
Chaîne concaténée.

## String::operator+(char_t) const method


Ajoute un caractère à la fin de la chaîne.

```cpp
String System::String::operator+(char_t x) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | char_t | Caractère à ajouter. |

### Return Value

Valeur de retour  
[String](../) résultat de concaténation.

## String::operator+(int) const method


Ajoute la représentation sous forme de chaîne d'une valeur entière à la fin de la chaîne.

```cpp
String System::String::operator+(int i) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | int | Valeur entière à convertir en chaîne et à ajouter. |

### Return Value

Valeur de retour  
[String](../) résultat de concaténation.

## String::operator+(uint32_t) const method


Ajoute la représentation sous forme de chaîne d'une valeur entière non signée à la fin de la chaîne.

```cpp
String System::String::operator+(uint32_t i) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| i | **uint32_t** | Valeur à convertir en chaîne et à ajouter. |

### Return Value

Valeur de retour  
[String](../) résultat de concaténation.

## String::operator+(double) const method


Ajoute la représentation sous forme de chaîne d'une valeur à virgule flottante à la fin de la chaîne.

```cpp
String System::String::operator+(double d) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| d | **double** | Valeur à convertir en chaîne et à ajouter. |

### Return Value

Valeur de retour  
[String](../) résultat de concaténation.

## String::operator+(int64_t) const method


Ajoute la représentation sous forme de chaîne d'une valeur entière à la fin de la chaîne.

```cpp
String System::String::operator+(int64_t v) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| v | **int64_t** | Valeur à convertir en chaîne et à ajouter. |

### Return Value

Valeur de retour  
[String](../) résultat de concaténation.

## String::operator+(const T\&) const method


Ajoute la représentation sous forme de chaîne d'un objet de type référence à la fin de la chaîne.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### Template parameters

| Paramètre | Description |
| --- | --- |
| T | type pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) à convertir en chaîne en utilisant l'appel [ToString()](../tostring/) et à ajouter à la chaîne actuelle. |

### Return Value

Valeur de retour  
[String](../) résultat de concaténation.

## String::operator+(const T\&) const method


Ajoute la représentation sous forme de chaîne d'un objet de type valeur à la fin de la chaîne.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### Template parameters

| Paramètre | Description |
| --- | --- |
| T | Type valeur sur lequel appeler [ToString()](../tostring/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) à convertir en chaîne en utilisant l'appel [ToString()](../tostring/) et à ajouter à la chaîne actuelle. |

### Return Value

Valeur de retour  
[String](../) résultat de concaténation.

## String::operator+(T) const method


Ajoute la représentation sous forme de chaîne d'une valeur booléenne à la fin de la chaîne.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### Template parameters

| Paramètre | Description |
| --- | --- |
| T | Type valeur à concaténer avec la chaîne. Doit être bool. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) valeur à convertir en chaîne et à ajouter. |

### Return Value

Valeur de retour  
[String](../) résultat de concaténation.

## See Also

* Classe [String](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)