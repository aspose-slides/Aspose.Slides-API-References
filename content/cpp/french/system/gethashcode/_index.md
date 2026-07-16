---
title: GetHashCode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un code de hachage pour la valeur scalaire spécifiée.
type: docs
weight: 2445
url: /fr/system/gethashcode/
---
## System::GetHashCode(const T\&) fonction


Renvoie un code de hachage pour la valeur scalaire spécifiée.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de la valeur pour laquelle la fonction génère le code de hachage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | La valeur pour laquelle générer le code de hachage |

### Valeur de retour

Le code de hachage généré pour la valeur spécifiée

## System::GetHashCode(const T\&) fonction


Renvoie un code de hachage pour l'objet spécifié.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet pour lequel la fonction génère le code de hachage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | Le [SmartPtr](../smartptr/) pointant vers l'objet pour lequel générer le code de hachage |

### Valeur de retour

Le code de hachage généré pour l'objet spécifié

## System::GetHashCode(const T\&) fonction


Renvoie un code de hachage pour l'objet spécifié qui est une exception.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet pour lequel la fonction génère le code de hachage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | L’enveloppe d’exception contenant l'objet pour lequel générer le code de hachage |

### Valeur de retour

Le code de hachage généré pour l'objet spécifié

## System::GetHashCode(const T\&) fonction


Renvoie un code de hachage pour l'objet spécifié qui n’est ni un pointeur intelligent ni une exception.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Le type de l'objet pour lequel la fonction génère le code de hachage |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | Une référence constante à l'objet pour lequel générer le code de hachage |

### Valeur de retour

Le code de hachage généré pour l'objet spécifié

## System::GetHashCode(const std::thread::id\&) fonction


Spécialisation pour std::thread::id ; renvoie le code de hachage pour l'objet thread spécifié.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Voir aussi

* Structure [IsSmartPtr](../issmartptr/)
* Structure [IsExceptionWrapper](../isexceptionwrapper/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)