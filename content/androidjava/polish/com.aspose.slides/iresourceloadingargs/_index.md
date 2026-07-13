---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Interfejs dla argumentów ładowania zasobów zewnętrznych.
type: docs
url: /pl/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Interfejs dla argumentów ładowania zasobów zewnętrznych.
## Metody

| Metoda | Opis |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Oryginalny URI zasobu określony w zaimportowanej prezentacji. |
| [getUri()](#getUri--) | URI zasobu używany do pobierania, jeśli [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) zwraca [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI zasobu używany do pobierania, jeśli [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) zwraca [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Ustawia dane zasobu dostarczone przez użytkownika, które są używane, jeśli [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) zwraca [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Oryginalny URI zasobu określony w zaimportowanej prezentacji.

**Zwraca:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI zasobu używany do pobierania, jeśli [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) zwraca [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Początkowo jest ustawiony na oryginalny URI zasobu, ale może zostać zmieniony na dowolną wartość.

**Zwraca:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI zasobu używany do pobierania, jeśli [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) zwraca [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Początkowo jest ustawiony na oryginalny URI zasobu, ale może zostać zmieniony na dowolną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Ustawia dane zasobu dostarczone przez użytkownika, które są używane, jeśli [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) zwraca [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| data | byte[] | Dostarczone dane zasobu byte[] |
