---
title: IResourceLoadingArgs class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs class

Interfaz para argumentos de carga de recursos externos.

El tipo IResourceLoadingArgs expone los siguientes miembros:

## Propiedades

| Property | Descripción |
| :- | :- |
| [`original_uri`](/slides/python-net/es/aspose.slides/iresourceloadingargs/original_uri/) | URI original del recurso tal como se especifica en la presentación importada. |
| [`uri`](/slides/python-net/es/aspose.slides/iresourceloadingargs/uri/) | URI del recurso que se utiliza para la descarga si **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            devuelve [`ResourceLoadingAction.DEFAULT`](/slides/python-net/es/aspose.slides/resourceloadingaction/DEFAULT). <br/>            Inicialmente se establece en la URI original del recurso, pero puede redefinirse a cualquier valor. |

## Métodos

| Method | Descripción |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/es/aspose.slides/iresourceloadingargs/set_data/#bytes) | Establece los datos proporcionados por el usuario del recurso que se utilizan si **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            devuelve [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/es/aspose.slides/resourceloadingaction/USER_PROVIDED). |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)