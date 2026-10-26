---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /de/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Schnittstelle für externe Ressourcen-Lade-Argumente.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Ursprüngliche URI der Ressource, wie in der importierten Präsentation angegeben. |
| [getUri()](#getUri--) | URI der Ressource, die zum Herunterladen verwendet wird, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) zurückgibt. |
| [setUri(String value)](#setUri-java.lang.String-) | URI der Ressource, die zum Herunterladen verwendet wird, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) zurückgibt. |
| [setData(byte[] data)](#setData-byte---) | Setzt vom Benutzer bereitgestellte Daten der Ressource, die verwendet werden, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) zurückgibt. |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Ursprüngliche URI der Ressource, wie in der importierten Präsentation angegeben.

**Rückgabe:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI der Ressource, die zum Herunterladen verwendet wird, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) zurückgibt. Anfangs ist sie auf die ursprüngliche URI der Ressource gesetzt, kann aber auf jeden beliebigen Wert neu definiert werden.

**Rückgabe:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI der Ressource, die zum Herunterladen verwendet wird, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) zurückgibt. Anfangs ist sie auf die ursprüngliche URI der Ressource gesetzt, kann aber auf jeden beliebigen Wert neu definiert werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Setzt vom Benutzer bereitgestellte Daten der Ressource, die verwendet werden, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) zurückgibt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Bereitgestellte Daten der Ressource byte[] |