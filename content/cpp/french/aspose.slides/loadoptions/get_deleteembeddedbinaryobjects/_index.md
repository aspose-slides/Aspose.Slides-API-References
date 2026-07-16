---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation.
type: docs
weight: 339
url: /fr/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() méthode


Détermine si [Aspose.Slides](../../) supprimera tous les objets binaires incorporés lors du chargement de la présentation.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Remarques


Les types des objets binaires incorporés :

* Projet VBA [IPresentation::VbaProject](../)
* Données incorporées OLE Object [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) données binaires [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Lire **bool**. 

La valeur par défaut est **false**. 

L'exemple suivant montre comment charger la présentation sans aucun objet binaire incorporé. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Voir aussi

* Classe [LoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)