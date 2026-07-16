---
title: Warning()
second_title: Référence de l'API Aspose.Slides pour C++
description: Méthode de rappel qui reçoit un avertissement et décide si l'opération doit être interrompue.
type: docs
weight: 1
url: /fr/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) méthode

Méthode de rappel qui reçoit un avertissement et décide si l'opération doit être interrompue.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Avertissement à traiter. |

### Valeur de retour

Décision d'arrêt [ReturnAction](../../returnaction/).

## Voir aussi

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IWarningInfo](../../iwarninginfo/)
* Classe [IWarningCallback](../)
* Espace de noms [Aspose::Slides::Warnings](../../)
* Bibliothèque [Aspose.Slides](../../../)