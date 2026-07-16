---
title: GetType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Implémente la traduction de typeof(). Surcharge pour les pointeurs intelligents.
type: docs
weight: 1
url: /fr/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) méthode

Implémente la traduction de typeof(). Surcharge pour les pointeurs intelligents.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type d'objet pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) pour obtenir [TypeInfo](../../typeinfo/) pour. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant la classe finale de l'objet passé.

## ObjectType::GetType(const T\&) méthode

Implémente la traduction de typeof(). Surcharge pour les structures.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de structure. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) pour obtenir [TypeInfo](../../typeinfo/) pour. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant la classe finale de l'objet passé.

## ObjectType::GetType(const T\&) méthode

Implémente la traduction de typeof(). Surcharge pour les exceptions.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type d'exception. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) pour obtenir [TypeInfo](../../typeinfo/) pour. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant la classe finale de l'objet passé.

## ObjectType::GetType(const T) méthode

Implémente la traduction de typeof(). Surcharge pour les types primitifs.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type primitif. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T | IGNORED |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant le type de l'objet passé.

## ObjectType::GetType(const T) méthode

Implémente la traduction de typeof(). Surcharge pour les types [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T | IGNORED |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant le type de l'objet passé.

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour les types primitifs.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type primitif. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant le type spécifié.

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour les types d'énumération.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type primitif. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant le type spécifié.

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour les structures et les pointeurs.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type primitif. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant la structure spécifiée.

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant la structure spécifiée.

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type MutlicastDelegate. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant la structure spécifiée.

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour les structures et les pointeurs.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type primitif. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant la structure spécifiée ou le type pointé si demandé pour [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) méthode

Implémente la traduction de typeof(). Surcharge pour le type chaîne.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type primitif. |

### Valeur de retour

Référence constante à la structure [TypeInfo](../../typeinfo/) décrivant le type [String](../../string/).

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() méthode

Implémente la traduction de typeof(). Surcharge pour [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Voir aussi

* Classe [ObjectType](../)
* Classe [TypeInfo](../../typeinfo/)
* Classe [String](../../string/)
* Structure [IsSmartPtr](../../issmartptr/)
* Structure [IsExceptionWrapper](../../isexceptionwrapper/)
* Structure [IsNullable](../../isnullable/)
* Structure [IsBoxable](../../isboxable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)