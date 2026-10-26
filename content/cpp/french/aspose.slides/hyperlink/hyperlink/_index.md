---
title: Hyperlink()
second_title: Référence API Aspose.Slides pour C++
description: Crée une instance d'un hyperlien.
type: docs
weight: 339
url: /fr/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) constructeur


Crée une instance d'un hyperlien.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) constructeur


Crée une instance d'un hyperlien qui pointe vers une diapositive spécifique. Remarque : l'hyperlien créé doit être affecté à un objet de la même présentation, sinon le lien sera enregistré comme NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Diapositive cible. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) constructeur


Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en écrasant les propriétés secondaires.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Hyperlien source |
| targetFrame | [System::String](../../../system/string/) | Cadre cible |
| tooltip | [System::String](../../../system/string/) | Texte de l'infobulle |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Hyperlink](../)
* Classe [ISlide](../../islide/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)