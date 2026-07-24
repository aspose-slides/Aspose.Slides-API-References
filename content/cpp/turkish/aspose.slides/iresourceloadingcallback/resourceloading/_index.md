---
title: ResourceLoading()
second_title: Aspose.Slides C++ API Referansı
description: Dış kaynakların yüklenmesini düzenleyen geri çağırma yöntemi.
type: docs
weight: 1
url: /tr/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) metodu

Dış kaynakların yüklenmesini düzenleyen geri çağırma metodu.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | Yüklenen kaynak verisi [IResourceLoadingArgs](../../iresourceloadingargs/). |

### Dönüş Değeri

Kaynak yükleme kararı [ResourceLoadingAction](../../resourceloadingaction/).

## Ayrıca

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IResourceLoadingArgs](../../iresourceloadingargs/)
* Sınıf [IResourceLoadingCallback](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)