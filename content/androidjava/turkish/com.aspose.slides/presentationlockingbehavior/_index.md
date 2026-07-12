---
title: PresentationLockingBehavior
second_title: Aspose.Slides for Android için Java API Referansı
description: Yükleme ve bir örnek üzerinde çalışırken kaynak dosya ya da java.io.InputStream'in ele alınmasıyla ilgili davranışı temsil eder.
type: docs
url: /tr/com.aspose.slides/presentationlockingbehavior/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Bir [IPresentation](../../com.aspose.slides/ipresentation) örneğiyle yükleme ve çalışma sırasında [IPresentation](../../com.aspose.slides/ipresentation) kaynağını (dosya veya java.io.InputStream) ele alma davranışını temsil eder.

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Kaynak, [IPresentation](../../com.aspose.slides/ipresentation) yapıcısına geçirilen parametredir. Aşağıdaki örnekte, kaynak "pres.pptx" dosyasıdır: Bu örnek için, kaynak ("pres.pptx" dosyası) bir [IPresentation](../../com.aspose.slides/ipresentation) örneği ömrü boyunca kilitli olacaktır, yani diğer süreç tarafından değiştirilemez veya silinemez.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Kaynak sadece [IPresentation](../../com.aspose.slides/ipresentation) yapıcı yürütmesi süresince kilitli olacaktır. |
| [KeepLocked](#KeepLocked) | Kaynak, [IPresentation](../../com.aspose.slides/ipresentation) örneğinin tüm ömrü boyunca, yok edilene kadar kilitli olacaktır. |

### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

Kaynak sadece [IPresentation](../../com.aspose.slides/ipresentation) yapıcı yürütmesi süresi boyunca kilitli olacaktır.

--------------------

Eğer ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) false olarak ayarlanırsa, tüm BLOB'lar belleğe yüklenecektir. Aksi takdirde, geçici dosyalar gibi başka yöntemler kullanılabilir.

--------------------

Bu davranış [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked)'dan daha yavaştır ve eğer kaynağın sahipliği [IPresentation](../../com.aspose.slides/ipresentation)'a devredilebiliyorsa, [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) kullanılması önerilir.

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Kaynak, [IPresentation](../../com.aspose.slides/ipresentation) örneğinin tüm ömrü boyunca, yok edilene kadar kilitli olacaktır.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) bu davranışı kullanmak için true olarak ayarlanmalıdır, aksi takdirde istisna fırlatılacaktır.

--------------------

Bu davranış önerilir, [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease)'den daha hızlıdır ve daha az bellek tüketir.