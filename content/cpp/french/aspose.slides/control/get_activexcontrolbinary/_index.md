---
title: get_ActiveXControlBinary()
second_title: Référence API Aspose.Slides pour C++
description: Spécifie la persistance d'un contrôle ActiveX lorsque la méthode utilisée pour le persister est soit PersistStream, PersistStreamInit ou PersistStorage.
type: docs
weight: 118
url: /fr/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() méthode


Spécifie la persistance d'un contrôle ActiveX lorsque la méthode utilisée pour le persister est soit PersistStream, PersistStreamInit ou PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Remarques


L'exemple suivant montre l'utilisation de la propriété ActiveXControlBinary pour modifier les propriétés ActiveX :
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

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Control](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)