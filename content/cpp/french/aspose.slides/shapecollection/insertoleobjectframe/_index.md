---
title: InsertOleObjectFrame()
second_title: Référence API Aspose.Slides for C++
description: Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 196
url: /fr/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) méthode


Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Arguments

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

## Remarques



Cet exemple montre l'insertion d'un objet OLE à la deuxième position :
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) méthode


Crée un nouveau cadre d'objet OLE et l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Arguments

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

Le cadre d'objet OLE nouvellement créé.

## Remarques



Ce chemin est stocké tel quel dans la présentation. Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture de la présentation depuis un répertoire différent.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOleObjectFrame](../../ioleobjectframe/)
* Classe [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Classe [ShapeCollection](../)
* Classe [String](../../../system/string/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)