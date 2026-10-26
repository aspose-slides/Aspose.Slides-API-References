---
title: IResourceLoadingArgs
second_title: Aspose.Slides für Java API Reference
description: Schnittstelle für Argumente zum Laden externer Ressourcen.
type: docs
url: /de/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Schnittstelle für Argumente zum Laden externer Ressourcen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Original-URI der Ressource wie in der importierten Präsentation angegeben. |
| [getUri()](#getUri--) | URI der Ressource, die zum Herunterladen verwendet wird, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) zurückgibt. |
| [setUri(String value)](#setUri-java.lang.String-) | URI der Ressource, die zum Herunterladen verwendet wird, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) zurückgibt. |
| [setData(byte[] data)](#setData-byte---) | Legt von Benutzer bereitgestellte Daten der Ressource fest, die verwendet werden, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) zurückgibt. |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Original-URI der Ressource wie in der importierten Präsentation angegeben.

**Rückgabewert:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI der Ressource, die zum Herunterladen verwendet wird, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) zurückgibt. Anfangs ist er auf den Original-URI der Ressource gesetzt, kann aber auf jeden Wert neu definiert werden.

**Rückgabewert:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI der Ressource, die zum Herunterladen verwendet wird, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) zurückgibt. Anfangs ist er auf den Original-URI der Ressource gesetzt, kann aber auf jeden Wert neu definiert werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Legt von Benutzer bereitgestellte Daten der Ressource fest, die verwendet werden, wenn [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | byte[] | Bereitgestellte Daten der Ressource byte[] |