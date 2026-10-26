---
title: LoadingStreamBehavior enumeration
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior énumération

Le **io.RawIOBase** passé à une méthode est considéré comme un Binary Large Object (BLOB) (voir la description [`IBlobManagementOptions`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions)). Les valeurs de cette énumération indiquent comment le **io.RawIOBase** doit être traité lorsqu'il est passé à la méthode. En fonction des exigences, différentes décisions peuvent être prises pour offrir le comportement le plus efficace.

Le type LoadingStreamBehavior expose les membres suivants :

## Champs

| Champ | Description |
| :- | :- |
| READ_STREAM_AND_RELEASE | Le flux sera lu jusqu’à la fin puis libéré - c’est-à-dire qu’il sera garanti que ce flux <br/> ne sera plus utilisé par une instance [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation) à l’avenir. Il peut être fermé par le code client <br/> ou utilisé de toute autre manière. |
| KEEP_LOCKED | Le flux sera verrouillé à l’intérieur de l’objet [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation), c’est-à-dire que la propriété du <br/> flux sera transférée. L’objet [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation) sera responsable de <br/> disposer correctement du flux lorsque cet objet sera lui-même disposé. <br/> Ce comportement est extrêmement utile lorsqu’il faut sérialiser un fichier BLOB volumineux (comme une grande <br/> vidéo ou audio -see [`IBlobManagementOptions`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions) description) et que l’on souhaite empêcher le chargement <br/> de ce fichier en mémoire ou d’autres problèmes de performance. Vous pouvez simplement ouvrir le **System.IO.FileStream** <br/> pour ce fichier et le transmettre à une méthode, en choisissant [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/fr/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### Voir aussi
* classe [`IBlobManagementOptions`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions)
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)