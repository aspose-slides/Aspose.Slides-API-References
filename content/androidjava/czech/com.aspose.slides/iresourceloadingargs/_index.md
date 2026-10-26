---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /cs/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Rozhraní pro argumenty načítání externích zdrojů.
## Metody

| Metoda | Popis |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Původní URI zdroje, jak je uvedeno v importované prezentaci. |
| [getUri()](#getUri--) | URI zdroje, které se použije pro stažení, pokud [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) vrátí [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI zdroje, které se použije pro stažení, pokud [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) vrátí [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Nastaví uživatelem poskytnutá data zdroje, která se použijí, pokud [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) vrátí [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Původní URI zdroje, jak je uvedeno v importované prezentaci.

**Vrací:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI zdroje, které se použije pro stažení, pokud [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) vrátí [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Původně je nastaveno na původní URI zdroje, ale může být předefinováno na libovolnou hodnotu.

**Vrací:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI zdroje, které se použije pro stažení, pokud [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) vrátí [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Původně je nastaveno na původní URI zdroje, ale může být předefinováno na libovolnou hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Nastaví uživatelem poskytnutá data zdroje, která se použijí, pokud [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) vrátí [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| data | byte[] | Poskytnutá data zdroje byte[] |