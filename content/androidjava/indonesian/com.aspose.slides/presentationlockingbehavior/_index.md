---
title: PresentationLockingBehavior
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili perilaku terkait penanganan file sumber atau java.io.InputStream saat memuat dan bekerja dengan sebuah instance.
type: docs
url: /id/com.aspose.slides/presentationlockingbehavior/
---
**Warisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Mewakili perilaku terkait penanganan sumber [IPresentation](../../com.aspose.slides/ipresentation) (file atau java.io.InputStream) saat memuat dan bekerja dengan sebuah instance [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Sumber adalah parameter yang diteruskan ke konstruktor [IPresentation](../../com.aspose.slides/ipresentation). Pada contoh di bawah, sumber adalah file "pres.pptx": Untuk contoh ini, sumber ("pres.pptx" file) akan dikunci selama masa hidup instance [IPresentation](../../com.aspose.slides/ipresentation), yaitu tidak dapat diubah atau dihapus oleh proses lain.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Sumber akan dikunci hanya selama waktu eksekusi konstruktor [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | Sumber akan dikunci selama seluruh masa hidup instance [IPresentation](../../com.aspose.slides/ipresentation), sampai akan dibuang. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

Sumber hanya akan dikunci selama eksekusi konstruktor [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Jika ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) diatur ke false, semua BLOB akan dimuat ke memori. Jika tidak, cara lain seperti file sementara mungkin akan digunakan.

--------------------

Perilaku ini lebih lambat daripada [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), dan jika memungkinkan untuk menyerahkan kepemilikan sumber ke [IPresentation](../../com.aspose.slides/ipresentation), disarankan untuk menggunakan [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Sumber akan dikunci selama seluruh masa hidup instance [IPresentation](../../com.aspose.slides/ipresentation), sampai ia dibuang.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) harus diatur ke true untuk menggunakan perilaku ini, jika tidak akan terjadi pengecualian.

--------------------

Perilaku ini direkomendasikan, lebih cepat dan mengkonsumsi memori lebih sedikit dibandingkan [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).