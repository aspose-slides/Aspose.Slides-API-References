---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Harici kaynakların yüklenmesini yönetmek için kullanılan geri çağırma arayüzü.
type: docs
url: /tr/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Harici kaynakların yüklenmesini yönetmek için kullanılan geri çağırma arayüzü.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Harici kaynakların yüklenmesini düzenleyen geri çağırma yöntemi. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Harici kaynakların yüklenmesini düzenleyen geri çağırma yöntemi.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Yüklenen kaynak verisi [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Dönüş Değeri:**
int - Kaynak yükleme kararı [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).