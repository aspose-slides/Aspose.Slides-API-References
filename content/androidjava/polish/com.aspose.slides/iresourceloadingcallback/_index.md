---
title: IResourceLoadingCallback
second_title: Aspose.Slides dla Androida przy użyciu interfejsu API Java
description: Interfejs wywołania zwrotnego używany do zarządzania ładowaniem zasobów zewnętrznych.
type: docs
url: /pl/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Interfejs wywołania zwrotnego używany do zarządzania ładowaniem zasobów zewnętrznych.
## Metody

| Metoda | Opis |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Metoda wywołania zwrotnego, która reguluje ładowanie zasobów zewnętrznych. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

Metoda wywołania zwrotnego, która reguluje ładowanie zasobów zewnętrznych.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Dane ładowanego zasobu [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Zwraca:**
int - Decyzja o ładowaniu zasobu [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).