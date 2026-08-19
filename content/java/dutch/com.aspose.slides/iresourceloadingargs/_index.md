---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /nl/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Interface voor argumenten voor het laden van externe bronnen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Originele URI van de bron zoals gespecificeerd in de geïmporteerde presentatie. |
| [getUri()](#getUri--) | URI van de bron die wordt gebruikt voor het downloaden als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) retourneert. |
| [setUri(String value)](#setUri-java.lang.String-) | URI van de bron die wordt gebruikt voor het downloaden als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) retourneert. |
| [setData(byte[] data)](#setData-byte---) | Stelt door de gebruiker verstrekte gegevens van de bron in die worden gebruikt als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) retourneert. |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Originele URI van de bron zoals gespecificeerd in de geïmporteerde presentatie.

**Retourwaarde:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI van de bron die wordt gebruikt voor het downloaden als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) retourneert. Aanvankelijk is deze ingesteld op de originele URI van de bron, maar kan naar elke waarde worden herschreven.

**Retourwaarde:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI van de bron die wordt gebruikt voor het downloaden als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) retourneert. Aanvankelijk is deze ingesteld op de originele URI van de bron, maar kan naar elke waarde worden herschreven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Stelt door de gebruiker verstrekte gegevens van de bron in die worden gebruikt als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) retourneert.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Geleverde gegevens van de bron byte[] |