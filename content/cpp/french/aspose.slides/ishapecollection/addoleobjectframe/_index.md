---
title: AddOleObjectFrame()
second_title: "Référence de l'API Aspose.Slides pour C++"
description: "Crée une nouvelle trame d'objet OLE et l'ajoute à la fin de la collection de formes."
type: docs
weight: 66
url: /fr/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) méthode

Crée une nouvelle trame d'objet OLE et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x de la nouvelle trame OLE, en points. |
| y | **float** | La coordonnée y de la nouvelle trame OLE, en points. |
| width | **float** | La largeur de la nouvelle trame OLE, en points. |
| height | **float** | La hauteur de la nouvelle trame OLE, en points. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Les informations de données OLE intégrées ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valeur de retour

Le [IOleObjectFrame](../../ioleobjectframe/) nouvellement créé.

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) méthode

Crée une nouvelle trame d'objet OLE et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x de la nouvelle trame OLE, en points. |
| y | **float** | La coordonnée y de la nouvelle trame OLE, en points. |
| width | **float** | La largeur de la nouvelle trame OLE, en points. |
| height | **float** | La hauteur de la nouvelle trame OLE, en points. |
| className | [System::String](../../../system/string/) | Le nom de classe de l'objet OLE. |
| path | [System::String](../../../system/string/) | Le chemin du fichier lié. |

### Valeur de retour

Le [IOleObjectFrame](../../ioleobjectframe/) nouvellement créé.

## Remarques

Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture de la présentation depuis un répertoire différent.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleObjectFrame](../../ioleobjectframe/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [IShapeCollection](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)