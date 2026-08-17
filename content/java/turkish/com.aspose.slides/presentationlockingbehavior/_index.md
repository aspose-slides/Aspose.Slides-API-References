---
title: PresentationLockingBehavior
second_title: Aspose.Slides for Java API Referansı
description: Bir örnek yüklerken ve onunla çalışırken  kaynak dosyayı veya  java.io.InputStream'i ele alma davranışını temsil eder.
type: docs
url: /tr/com.aspose.slides/presentationlockingbehavior/
---
**Kalıtım:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Bir [IPresentation](../../com.aspose.slides/ipresentation) örneğiyle çalışırken [IPresentation](../../com.aspose.slides/ipresentation) kaynağını (dosya veya java.io.InputStream) yükleme ve kullanma davranışını temsil eder.

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Kaynak, [IPresentation](../../com.aspose.slides/ipresentation) yapıcısına geçirilen parametredir. Aşağıdaki örnekte, kaynak "pres.pptx" dosyasıdır: Bu örnek için, kaynak ("pres.pptx" dosyası) bir [IPresentation](../../com.aspose.slides/ipresentation) örnek ömrü boyunca kilitlenir, yani diğer işlem tarafından değiştirilemez veya silinemez.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Kaynak, yalnızca [IPresentation](../../com.aspose.slides/ipresentation) yapıcı çalışması süresince kilitli olacaktır. |
| [KeepLocked](#KeepLocked) | Kaynak, [IPresentation](../../com.aspose.slides/ipresentation) örneğinin tüm ömrü boyunca, dispose edilene kadar kilitli olacaktır. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

Kaynak, yalnızca [IPresentation](../../com.aspose.slides/ipresentation) yapıcı çalışması süresince kilitli olacaktır.

--------------------

Eğer ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) false olarak ayarlanırsa, tüm BLOB'lar belleğe yüklenecektir. Aksi takdirde, geçici dosyalar gibi başka yollar kullanılabilir.

--------------------

Bu davranış, [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked)'den daha yavaştır ve kaynak sahipliğini [IPresentation](../../com.aspose.slides/ipresentation)'ye geçirmek mümkünse, [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) kullanılması önerilir.

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Kaynak, [IPresentation](../../com.aspose.slides/ipresentation) örneğinin tüm ömrü boyunca, dispose edilene kadar kilitli olacaktır.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) bu davranışı kullanmak için true olarak ayarlanmalıdır, aksi takdirde istisna fırlatılacaktır.

--------------------

Bu davranış önerilir, [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease)'den daha hızlıdır ve daha az bellek tüketir.