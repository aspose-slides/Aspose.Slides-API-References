---
title: ResourceLoadingAction
second_title: Aspose.Slides para Referência da API C++
description: Especifica o modo de carregamento de recursos externos.
type: docs
weight: 6761
url: /pt/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction enum

Especifica o modo de carregamento de recursos externos.

```cpp
enum class ResourceLoadingAction
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../) carregará o recurso externo como de costume. |
| Skip | 1 | [Aspose.Slides](../) pulará o carregamento do recurso externo. Apenas o link sem dados será armazenado para uma imagem. |
| UserProvided | 2 | [Aspose.Slides](../) usará o array de bytes fornecido pelo usuário em [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/) como dados da imagem. |

## Veja também

* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)