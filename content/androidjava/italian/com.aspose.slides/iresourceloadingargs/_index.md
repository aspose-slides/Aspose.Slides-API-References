---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Interfaccia per gli argomenti di caricamento delle risorse esterne.
type: docs
url: /it/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Interfaccia per gli argomenti di caricamento delle risorse esterne.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | URI originale della risorsa come specificato nella presentazione importata. |
| [getUri()](#getUri--) | URI della risorsa utilizzato per il download se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) restituisce [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI della risorsa utilizzato per il download se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) restituisce [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Imposta i dati forniti dall'utente della risorsa che viene utilizzata se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) restituisce [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

URI originale della risorsa come specificato nella presentazione importata.

**Restituisce:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```

URI della risorsa utilizzato per il download se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) restituisce [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Inizialmente è impostato sull'URI originale della risorsa, ma può essere ridefinito a qualsiasi valore.

**Restituisce:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

URI della risorsa utilizzato per il download se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) restituisce [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Inizialmente è impostato sull'URI originale della risorsa, ma può essere ridefinito a qualsiasi valore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

Imposta i dati forniti dall'utente della risorsa che viene utilizzata se [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) restituisce [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | Dati forniti della risorsa byte[] |