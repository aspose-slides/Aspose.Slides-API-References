---
title: IResourceLoadingArgs class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs Klasse

Interface für externe Ressourcendeladen-Argumente.

Der Typ IResourceLoadingArgs stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`original_uri`](/slides/python-net/de/aspose.slides/iresourceloadingargs/original_uri/) | Ursprüngliche URI der Ressource, wie in der importierten Präsentation angegeben. |
| [`uri`](/slides/python-net/de/aspose.slides/iresourceloadingargs/uri/) | URI der Ressource, die zum Herunterladen verwendet wird, wenn **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            returns [`ResourceLoadingAction.DEFAULT`](/slides/python-net/de/aspose.slides/resourceloadingaction/DEFAULT). <br/>            Anfangs ist sie auf die ursprüngliche URI der Ressource gesetzt, kann jedoch auf einen beliebigen Wert neu definiert werden. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/de/aspose.slides/iresourceloadingargs/set_data/#bytes) | Setzt benutzerbereitgestellte Daten der Ressource, die verwendet werden, wenn **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            returns [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/de/aspose.slides/resourceloadingaction/USER_PROVIDED). |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)