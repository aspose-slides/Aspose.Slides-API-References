---
title: ConvertAll()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une liste d'éléments convertis en un type différent.
type: docs
weight: 352
url: /fr/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) méthode


Crée une liste d'éléments convertis en un type différent.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| OutputType | Type d'élément de la liste de sortie. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Convertisseur à utiliser pour la conversion des éléments. |

### Valeur de retour

Une liste nouvellement créée d'éléments convertis.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Classe [List](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)