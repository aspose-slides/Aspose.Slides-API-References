---
title: MakeObject()
second_title: Aspose.Slides pour C++ – Référence de l'API
description: Crée un objet sur le tas et renvoie un pointeur partagé vers celui-ci.
type: docs
weight: 2848
url: /fr/system/makeobject/
---
## System::MakeObject(Args\&&...) fonction


Crée un objet sur le tas et renvoie un pointeur partagé vers celui-ci.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Classe à instancier. |
| Args | Types des arguments du constructeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Arguments du constructeur. |

### Valeur de retour

[SmartPtr](../smartptr/) vers l'objet nouvellement créé, toujours en mode partagé.

## System::MakeObject(Args\&&...) fonction


Crée un objet sur le tas et renvoie un pointeur partagé vers celui-ci.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [SmartPtr](../smartptr/) de la classe à instancier. |
| Args | Types des arguments du constructeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Arguments du constructeur. |

### Valeur de retour

[SmartPtr](../smartptr/) vers l'objet nouvellement créé, toujours en mode partagé.

## Voir également

* Classe [SmartPtr](../smartptr/)
* Structure [IsSmartPtr](../issmartptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)