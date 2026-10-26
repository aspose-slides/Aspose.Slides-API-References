---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation.
type: docs
weight: 352
url: /fr/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) méthode


Détermine si [Aspose.Slides](../../) supprimera tous les objets binaires incorporés lors du chargement de la présentation.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Remarques


Les types des objets binaires incorporés :

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Écrire **bool**. 

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