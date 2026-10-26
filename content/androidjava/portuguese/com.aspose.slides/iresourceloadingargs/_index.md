---
title: IResourceLoadingArgs
second_title: Aspose.Slides para Android via Referência da API Java
description: Interface para argumentos de carregamento de recursos externos.
type: docs
url: /pt/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Interface para argumentos de carregamento de recursos externos.
## Métodos

| Método | Descrição |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | URI original do recurso conforme especificado na apresentação importada. |
| [getUri()](#getUri--) | URI do recurso que é usado para download se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) retornar [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI do recurso que é usado para download se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) retornar [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Define os dados fornecidos pelo usuário do recurso que são usados se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) retornar [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

URI original do recurso conforme especificado na apresentação importada.

**Retorna:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```

URI do recurso que é usado para download se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) retornar [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Inicialmente, ele é definido como a URI original do recurso, mas pode ser redefinido para qualquer valor.

**Retorna:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

URI do recurso que é usado para download se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) retornar [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Inicialmente, ele é definido como a URI original do recurso, mas pode ser redefinido para qualquer valor.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

Define os dados fornecidos pelo usuário do recurso que são usados se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) retornar [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] | Dados fornecidos do recurso byte[] |