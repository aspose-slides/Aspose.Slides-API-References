---
title: operator>()
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 2094
url: /fr/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) fonction

```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```

## System::operator>(std::nullptr_t, const DateTimeOffset\&) fonction

```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```

## System::operator>(std::nullptr_t, const Nullable\<T\>\&) fonction

Renvoie toujours false.

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```

## System::operator>(const T1\&, const Nullable\<T2\>\&) fonction

Détermine si la valeur spécifiée est supérieure à la valeur représentée par l'objet [Nullable](../nullable/) spécifié en appliquant [operator>()](./) à ces valeurs.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### Valeur de retour

Vrai si le premier comparand est supérieur au second comparand, sinon - false

## System::operator>(std::nullptr_t, TimeSpan) fonction

```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## Voir aussi

* Classe [DateTime](../datetime/)
* Classe [DateTimeOffset](../datetimeoffset/)
* Classe [Nullable](../nullable/)
* Classe [TimeSpan](../timespan/)
* Structure [IsNullable](../isnullable/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)