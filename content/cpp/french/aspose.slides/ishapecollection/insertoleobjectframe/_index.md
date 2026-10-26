---
title: InsertOleObjectFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 79
url: /fr/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index de base zéro à lequel insérer le cadre d'objet OLE. |
| x | **float** | La coordonnée x du nouveau cadre OLE, en points. |
| y | **float** | La coordonnée y du nouveau cadre OLE, en points. |
| width | **float** | La largeur du nouveau cadre OLE, en points. |
| height | **float** | La hauteur du nouveau cadre OLE, en points. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Les informations de données OLE incorporées ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Valeur de retour

Le [IOleObjectFrame](../../ioleobjectframe/) nouvellement créé.

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) method

Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index de base zéro à lequel insérer le cadre d'objet OLE. |
| x | **float** | La coordonnée x du nouveau cadre OLE, en points. |
| y | **float** | La coordonnée y du nouveau cadre OLE, en points. |
| width | **float** | La largeur du nouveau cadre OLE, en points. |
| height | **float** | La hauteur du nouveau cadre OLE, en points. |
| className | [System::String](../../../system/string/) | Le nom de classe de l'objet OLE. |
| path | [System::String](../../../system/string/) | Le chemin du fichier lié. |

### Valeur de retour

Le [IOleObjectFrame](../../ioleobjectframe/) nouvellement créé.

## Remarques

Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture de la présentation depuis un répertoire différent.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)