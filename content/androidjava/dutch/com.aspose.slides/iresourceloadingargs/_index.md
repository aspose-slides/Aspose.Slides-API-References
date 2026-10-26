---
title: IResourceLoadingArgs
second_title: Aspose.Slides voor Android via Java API-referentie
description: Interface voor argumenten bij het laden van externe resources.
type: docs
url: /nl/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Interface voor argumenten bij het laden van externe resources.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Originele URI van de bron zoals gespecificeerd in de geïmporteerde presentatie. |
| [getUri()](#getUri--) | URI van de bron die wordt gebruikt voor het downloaden als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) teruggeeft. |
| [setUri(String value)](#setUri-java.lang.String-) | URI van de bron die wordt gebruikt voor het downloaden als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) teruggeeft. |
| [setData(byte[] data)](#setData-byte---) | Stelt gebruikersgegevens van de bron in die worden gebruikt als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) teruggeeft. |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Originele URI van de bron zoals gespecificeerd in de geïmporteerde presentatie.

**Retour:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI van de bron die wordt gebruikt voor het downloaden als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) teruggeeft. Aanvankelijk is deze ingesteld op de originele URI van de bron, maar kan naar elke waarde worden hergedefinieerd.

**Retour:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI van de bron die wordt gebruikt voor het downloaden als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) teruggeeft. Aanvankelijk is deze ingesteld op de originele URI van de bron, maar kan naar elke waarde worden hergedefinieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Stelt door de gebruiker geleverde gegevens van de bron in die worden gebruikt als [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) teruggeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | byte[] | Geleverde gegevens van de bron byte[] |