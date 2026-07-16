---
title: UpdateDocumentProperties()
second_title: Référence de l'API Aspose.Slides pour C++
description: Met à jour les propriétés de la présentation liée.
type: docs
weight: 92
url: /fr/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) méthode

Met à jour les propriétés de la présentation liée.

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | Propriétés du document [IDocumentProperties](../../idocumentproperties/) |

## Remarques

Cet exemple montre comment appeler la méthode [IPresentationInfo::UpdateDocumentProperties](./) pour mettre à jour les propriétés du document renvoyées par l'appel de la méthode [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/). 
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
* Classe [IPresentationInfo](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)