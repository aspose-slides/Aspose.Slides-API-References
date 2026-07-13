---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
url: /id/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Antarmuka callback yang digunakan untuk mengelola pemuatan sumber daya eksternal.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Metode callback yang mengatur pemuatan sumber daya eksternal. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

Metode callback yang mengatur pemuatan sumber daya eksternal.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Data sumber daya yang dimuat [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Mengembalikan:**
int - Keputusan pemuatan sumber daya [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).