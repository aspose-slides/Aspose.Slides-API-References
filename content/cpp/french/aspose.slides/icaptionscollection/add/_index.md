---
title: Add()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute des sous-titres fermés WebVTT à la fin de la collection.
type: docs
weight: 27
url: /fr/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) méthode

Ajoute des sous-titres fermés WebVTT à la fin de la collection.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Le libellé des sous-titres fermés. |
| filePath | [System::String](../../../system/string/) | Le chemin du fichier WebVTT. |

### Valeur de retour

L'instance [ICaptions](../../icaptions/) ajoutée.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) méthode

Ajoute des sous-titres fermés WebVTT à la fin de la collection à partir d'un flux.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Le libellé des sous-titres fermés. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Le flux d'entrée contenant les données au format WebVTT. |

### Valeur de retour

L'instance [ICaptions](../../icaptions/) ajoutée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptions](../../icaptions/)
* Classe [String](../../../system/string/)
* Classe [ICaptionsCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)