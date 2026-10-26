---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /es/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Interfaz para argumentos de carga de recursos externos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | URI original del recurso tal como se especifica en la presentación importada. |
| [getUri()](#getUri--) | URI del recurso que se usa para descargar si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) devuelve [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI del recurso que se usa para descargar si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) devuelve [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Establece los datos proporcionados por el usuario del recurso que se usan si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) devuelve [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


URI original del recurso tal como se especifica en la presentación importada.

**Devuelve:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI del recurso que se usa para descargar si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) devuelve [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Inicialmente se establece en la URI original del recurso, pero puede redefinirse a cualquier valor.

**Devuelve:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI del recurso que se usa para descargar si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) devuelve [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Inicialmente se establece en la URI original del recurso, pero puede redefinirse a cualquier valor.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Establece los datos proporcionados por el usuario del recurso que se usan si [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) devuelve [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Datos proporcionados del recurso byte[] |