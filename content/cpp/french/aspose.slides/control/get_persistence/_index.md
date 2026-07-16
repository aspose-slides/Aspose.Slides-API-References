---
title: get_Persistence()
second_title: Référence API Aspose.Slides pour C++
description: Obtient la méthode utilisée pour stocker les propriétés du contrôle ActiveX. Lecture seule PersistenceType.
type: docs
weight: 1
url: /fr/aspose.slides/control/get_persistence/
---
## Méthode Control::get_Persistence()

Obtient la méthode utilisée pour stocker les propriétés du contrôle ActiveX. Lecture seule [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Remarques

L'exemple suivant montre l'utilisation de la propriété Persistence pour vérifier si les propriétés de l'objet ActiveX peuvent être modifiées en tant que propriétés ActiveX basées sur XML :
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Utilisez votre propre méthode pour gérer les propriétés ActiveX stockées dans son fichier binaire
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Voir aussi

* Énumération [PersistenceType](../../persistencetype/)
* Classe [Control](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)