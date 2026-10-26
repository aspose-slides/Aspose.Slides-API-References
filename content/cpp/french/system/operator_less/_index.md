---
title: operator<()
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 2068
url: /fr/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) fonction




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) fonction




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) fonction


Renvoie toujours false.

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) fonction


Détermine si la valeur spécifiée est inférieure à la valeur représentée par l'objet [Nullable](../nullable/) spécifié en appliquant [operator<()](./) à ces valeurs.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Le type de la première valeur comparée |
| T2 | Le type sous-jacent de l'objet [Nullable](../nullable/) qui représente la deuxième valeur comparée |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| some | const T1\& | Une référence constante à la valeur qui doit être utilisée comme premier comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | Une référence constante à l'objet [Nullable](../nullable/) dont la valeur représentée doit être utilisée comme deuxième comparand |

### Valeur de retour

Vrai si le premier comparand est inférieur au second comparand, sinon - false

## System::operator<(std::nullptr_t, TimeSpan) fonction




```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## Voir aussi

* Classe [DateTime](../datetime/)
* Classe [DateTimeOffset](../datetimeoffset/)
* Classe [Nullable](../nullable/)
* Classe [TimeSpan](../timespan/)
* Structure [IsNullable](../isnullable/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)