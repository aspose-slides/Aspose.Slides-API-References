---
title: IResourceLoadingCallback
second_title: Aspose.Slides para Android via Referência da API Java
description: Interface de retorno de chamada usada para gerenciar o carregamento de recursos externos.
type: docs
url: /pt/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Interface de retorno de chamada usada para gerenciar o carregamento de recursos externos.
## Métodos

| Método | Descrição |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Método de retorno de chamada que regula o carregamento de recursos externos. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Método de retorno de chamada que regula o carregamento de recursos externos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Os dados do recurso de carregamento [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Retorna:**
int - A decisão de carregamento do recurso [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).