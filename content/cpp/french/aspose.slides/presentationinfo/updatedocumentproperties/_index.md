---
title: UpdateDocumentProperties()
second_title: Référence de l'API Aspose.Slides pour C++
description: Met à jour les propriétés de la présentation liée.
type: docs
weight: 92
url: /fr/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) méthode


Met à jour les propriétés de la présentation liée.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## Remarques


Cet exemple montre comment appeler la [PresentationInfo::UpdateDocumentProperties](./) méthode pour mettre à jour les propriétés du document renvoyées par l’appel de la [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) méthode. 
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDocumentProperties](../../idocumentproperties/)
* Classe [PresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)