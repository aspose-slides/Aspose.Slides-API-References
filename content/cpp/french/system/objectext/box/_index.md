---
title: Box()
second_title: Référence de l'API Aspose.Slides pour C++
description: Encapsule les types de valeur pour les convertir en Object. Implémentation pour les types enum.
type: docs
weight: 40
url: /fr/system/objectext/box/
---
## ObjectExt::Box(const T\&) méthode


Encapsule les types de valeur pour les convertir en [Object](../../object/). Implémentation pour les types enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) valeur à emballer. |

### Valeur de retour

Pointeur intelligent vers l'objet conservant la valeur emballée.

## ObjectExt::Box(const T\&) méthode


Encapsule les types de valeur pour les convertir en [Object](../../object/). Implémentation pour les types non enum.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | Valeur à emballer. |

### Valeur de retour

Pointeur intelligent vers l'objet conservant la valeur emballée.

## ObjectExt::Box(const T\&) méthode


Encapsule les types [Nullable](../../nullable/) pour les convertir en [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const T\& | Valeur à emballer. |

### Valeur de retour

Pointeur intelligent vers l'objet conservant la valeur emballée.

## ObjectExt::Box(const String\&) méthode


Encapsule les valeurs de chaîne.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Valeur à emballer. |

### Valeur de retour

Valeur encapsulée ou null, si la chaîne source est null.

## Voir également

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Classe [String](../../string/)
* Structure [IsNullable](../../isnullable/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)