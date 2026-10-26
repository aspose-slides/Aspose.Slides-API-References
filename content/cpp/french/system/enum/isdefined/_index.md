---
title: IsDefined()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si la valeur spécifiée est un membre du type d'énumération E.
type: docs
weight: 27
url: /fr/system/enum/isdefined/
---
## Enum::IsDefined(E) méthode

Détermine si la valeur spécifiée est un membre du type d'énumération **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | E | La valeur à vérifier |

### Valeur de retour

True si **value** est un membre de l’énumération **E**, sinon - false

## Enum::IsDefined(T) méthode

Détermine si la valeur spécifiée est un membre du type d'énumération **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T | La valeur à vérifier |

### Valeur de retour

True si **value** est un membre de l’énumération **T**, sinon - false

## Enum::IsDefined(const String\&) méthode

Détermine si la valeur portant le nom spécifié fait partie des membres de l’énumération **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../string/)\& | Le nom à vérifier |

### Valeur de retour

True si un membre de l’énumération **E** avec le nom spécifié existe.

## Voir aussi

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)