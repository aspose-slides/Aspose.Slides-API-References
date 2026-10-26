---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Referansı
description: Dış kaynak yüklemeyi yönetmek için kullanılan geri arama arayüzü.
type: docs
url: /tr/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Dış kaynak yüklemeyi yönetmek için kullanılan geri arama arayüzü.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Dış kaynak yüklemeyi düzenleyen geri arama metodu. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Dış kaynak yüklemeyi düzenleyen geri arama metodu.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Yüklenen kaynak verileri [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Dönüş:**  
int - Kaynak yükleme kararı [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).