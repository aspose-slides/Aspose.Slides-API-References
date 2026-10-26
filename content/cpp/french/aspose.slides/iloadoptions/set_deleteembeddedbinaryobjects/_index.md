---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Référence API Aspose.Slides pour C++
description: Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation.
type: docs
weight: 352
url: /fr/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) méthode

Détermine si [Aspose.Slides](../../) supprimera tous les objets binaires intégrés lors du chargement de la présentation.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Remarques

Les types d'objets binaires intégrés :

* Projet VBA [IPresentation::VbaProject](../)
* données intégrées d'objet OLE [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) données binaires [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Écrire **bool**. 

Valeur par défaut : **false**. 

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