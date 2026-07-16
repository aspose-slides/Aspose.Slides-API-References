---
title: SendWarning()
second_title: Référence de l'API Aspose.Slides pour C++
description: Si receiver n'est pas null, termine l'avertissement vers un receiver spécifié et lève l'exception AbortRequestedException si receiver décide d'annuler une opération.
type: docs
weight: 27
url: /fr/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) méthode


Si receiver n'est pas null, termine l'avertissement vers un receiver spécifié et lève l'exception AbortRequestedException si receiver décide d'annuler une opération.

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | Objet receiver [IWarningCallback](../../iwarningcallback/) |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IWarningCallback](../../iwarningcallback/)
* Classe [IWarningInfo](../)
* Espace de noms [Aspose::Slides::Warnings](../../)
* Bibliothèque [Aspose.Slides](../../../)