---
title: IResourceLoadingArgs class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs classe

Interface para argumentos de carregamento de recursos externos.

O tipo IResourceLoadingArgs expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`original_uri`](/slides/python-net/pt/aspose.slides/iresourceloadingargs/original_uri/) | URI original do recurso conforme especificado na apresentação importada. |
| [`uri`](/slides/python-net/pt/aspose.slides/iresourceloadingargs/uri/) | URI do recurso que é usado para download se **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            returns [`ResourceLoadingAction.DEFAULT`](/slides/python-net/pt/aspose.slides/resourceloadingaction/DEFAULT). <br/>            Inicialmente é definido como a URI original do recurso, mas pode ser redefinido para qualquer valor. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/pt/aspose.slides/iresourceloadingargs/set_data/#bytes) | Define os dados fornecidos pelo usuário do recurso que são usados se **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            returns [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/pt/aspose.slides/resourceloadingaction/USER_PROVIDED). |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)