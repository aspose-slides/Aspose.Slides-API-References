---
title: Cast()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit le pointeur en son propre type.
type: docs
weight: 287
url: /fr/system/smartptr/cast/
---
## SmartPtr::Cast() const méthode

Convertit le pointeur en son propre type.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Y | Type cible de l'objet pointé. |
| Check | Indicateurs pour lancer une exception si aucun cast n'est disponible. |

### Valeur de retour

Pointeur du type modifié qui est toujours en mode partagé.

## SmartPtr::Cast() const méthode

Convertit le pointeur en type de base en utilisant static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Y | Type cible de l'objet pointé. |
| Check | Indicateurs pour lancer une exception si aucun cast n'est disponible. |

### Valeur de retour

Pointeur du type modifié qui est toujours en mode partagé.

## SmartPtr::Cast() const méthode

Convertit le pointeur en type dérivé en utilisant dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Y | Type cible de l'objet pointé. |
| Check | Indicateurs pour lancer une exception si aucun cast n'est disponible. |

### Valeur de retour

Pointeur du type modifié qui est toujours en mode partagé. Lance InvalidCastException si aucune conversion n'est disponible.

## SmartPtr::Cast() const méthode

Convertit le pointeur en type dérivé en utilisant dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| Y | Type cible de l'objet pointé. |
| Check | Indicateurs pour lancer une exception si aucun cast n'est disponible. |

### Valeur de retour

Pointeur du type modifié qui est toujours en mode partagé. Retourne nullptr si aucune conversion n'est disponible.

## Voir aussi

* Classe [SmartPtr](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)