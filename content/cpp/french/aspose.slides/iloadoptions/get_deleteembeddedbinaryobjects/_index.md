---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation.
type: docs
weight: 339
url: /fr/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() méthode


Détermine si [Aspose.Slides](../../) supprimera tous les objets binaires intégrés lors du chargement de la présentation.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Remarques


Les types des objets binaires intégrés:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) données binaires [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Lire **bool**. 

La valeur par défaut est **false**. 

L'exemple suivant montre comment charger la présentation sans aucun objet binaire intégré. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## Voir aussi

* Classe [ILoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)