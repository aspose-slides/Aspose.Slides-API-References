---
title: operator+()
second_title: Référence de l'API Aspose.Slides pour C++
description: Retourne une nouvelle instance de la classe Decimal qui représente une valeur correspondant à la somme de la valeur spécifiée et de la valeur représentée par l'objet Decimal spécifié.
type: docs
weight: 2159
url: /fr/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) fonction


Retourne une nouvelle instance de la classe [Decimal](../decimal/) qui représente une valeur qui est la somme de la valeur spécifiée et de la valeur représentée par l'objet [Decimal](../decimal/) spécifié.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const T\& | Le premier opérande |
| d | const [Decimal](../decimal/)\& | La référence constante à l'objet [Decimal](../decimal/) représentant le deuxième opérande |

### Valeur de retour

Une nouvelle instance de la classe [Decimal](../decimal/) qui représente une valeur qui est la somme de **x** et de la valeur représentée par **d**.

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) fonction


Connecte tous les rappels du délégué de droite à la fin de la liste de rappels du délégué de gauche.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Le délégué auquel les rappels sont ajoutés. |
| rhv | MulticastDelegate\<T\> | Le délégué dont les rappels sont ajoutés. |

### Valeur de retour

Retourne un délégué qui contient les rappels de la valeur de gauche, puis ceux de la valeur de droite.

## System::operator+(const T1\&, const Nullable\<T2\>\&) fonction


Additionne des valeurs non nullables et nullables.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type d'opérande gauche. |
| T2 | Type d'opérande droit. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| some | const T1\& | Opérande gauche. |
| other | const [Nullable](../nullable/)\<T2\>\& | Opérande droit. |

### Valeur de retour

Résultat de l'addition.

## System::operator+(T\&, const String\&) fonction


[String](../string/) concaténation.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [String](../string/) type littéral. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | T\& | Littéral à concaténer à la chaîne. |
| right | const [String](../string/)\& | [String](../string/) à concaténer. |

### Valeur de retour

Chaîne concaténée.

## System::operator+(T\&, const String\&) fonction


[String](../string/) concaténation.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [String](../string/) type pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | T\& | [String](../string/) pointeur à concaténer à la chaîne. |
| right | const [String](../string/)\& | [String](../string/) à concaténer. |

### Valeur de retour

Chaîne concaténée.

## System::operator+(const char_t, const String\&) fonction


[String](../string/) concaténation.

```cpp
String System::operator+(const char_t left, const String &right)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | const char_t | Caractère à concaténer à la chaîne. |
| right | const [String](../string/)\& | [String](../string/) à concaténer. |

### Valeur de retour

Chaîne concaténée.

## Voir aussi

* Classe [Decimal](../decimal/)
* Classe [Nullable](../nullable/)
* Classe [String](../string/)
* Structure [IsStringLiteral](../isstringliteral/)
* Structure [IsStringPointer](../isstringpointer/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)