---
title: PresentationLockingBehavior
second_title: Aspose.Slides for Java API 參考文件
description: 表示在載入並使用實例時，處理  來源檔案或  java.io.InputStream 的行為。
type: docs
url: /zh-hant/com.aspose.slides/presentationlockingbehavior/
---
**Inheritance:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

表示在載入及使用 [IPresentation](../../com.aspose.slides/ipresentation) 實例時，處理 [IPresentation](../../com.aspose.slides/ipresentation) 來源（檔案或 java.io.InputStream）的行為。

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

來源是傳遞給 [IPresentation](../../com.aspose.slides/ipresentation) 建構式的參數。以下範例中，來源為 "pres.pptx" 檔案：對於此範例，來源（"pres.pptx" 檔案）將在 [IPresentation](../../com.aspose.slides/ipresentation) 實例的生命週期內被鎖定，也就是說其他程序無法變更或刪除它。
## 欄位

| 欄位 | 說明 |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | 來源僅在 [IPresentation](../../com.aspose.slides/ipresentation) 建構式執行期間被鎖定。 |
| [KeepLocked](#KeepLocked) | 來源將在 [IPresentation](../../com.aspose.slides/ipresentation) 實例的整個生命週期內被鎖定，直至其被釋放。 |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

來源僅在 [IPresentation](../../com.aspose.slides/ipresentation) 建構式執行期間被鎖定。

--------------------

如果 ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) 設為 false，所有 BLOB 皆會載入記憶體。否則，可能會使用其他方式，例如暫存檔案。

--------------------

此行為較 [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) 緩慢，若能將來源的所有權傳遞給 [IPresentation](../../com.aspose.slides/ipresentation)，建議使用 [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked)。

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

來源將在 [IPresentation](../../com.aspose.slides/ipresentation) 實例的整個生命週期內被鎖定，直至其被釋放。

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) 必須設為 true 才能使用此行為，否則會拋出例外。

--------------------

建議使用此行為，因為它比 [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease) 更快且佔用較少記憶體。