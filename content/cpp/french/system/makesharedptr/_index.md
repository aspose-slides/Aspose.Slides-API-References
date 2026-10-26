---
title: MakeSharedPtr()
second_title: Référence API Aspose.Slides pour C++
description: Convertit un pointeur brut en pointeur intelligent.
type: docs
weight: 2861
url: /fr/system/makesharedptr/
---
## System::MakeSharedPtr(X *) fonction


Convertit un pointeur brut en pointeur intelligent.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | Type du pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| p | X * | Pointeur brut vers l'objet. |

### Valeur de retour

Pointeur intelligent partagé vers l'objet.

## System::MakeSharedPtr(const X *) fonction


Convertit un pointeur brut en pointeur intelligent. Surcharge pour les pointeurs const. Utile, par exemple, lors de l'utilisation de la variable 'this' dans les méthodes C# traduites en const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| X | Type du pointeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| p | const X * | Pointeur brut vers l'objet. |

### Valeur de retour

Pointeur intelligent partagé vers l'objet.

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)