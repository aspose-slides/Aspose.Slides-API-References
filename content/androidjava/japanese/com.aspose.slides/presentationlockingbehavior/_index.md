---
title: PresentationLockingBehavior
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: インスタンスをロードして操作する際に、ソースファイルまたは java.io.InputStream を扱う動作を表します。
type: docs
url: /ja/com.aspose.slides/presentationlockingbehavior/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

[IPresentation](../../com.aspose.slides/ipresentation) ソース（ファイルまたは java.io.InputStream）をロードし、[IPresentation](../../com.aspose.slides/ipresentation) のインスタンスで使用する際の動作を表します。

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

ソースは [IPresentation](../../com.aspose.slides/ipresentation) コンストラクタに渡されるパラメータです。以下の例では、ソースは "pres.pptx" ファイルです。この例では、ソース（"pres.pptx" ファイル）は [IPresentation](../../com.aspose.slides/ipresentation) インスタンスの存続期間中ロックされ、他のプロセスによって変更または削除できません。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | ソースは [IPresentation](../../com.aspose.slides/ipresentation) コンストラクタの実行中のみロックされます。 |
| [KeepLocked](#KeepLocked) | ソースは [IPresentation](../../com.aspose.slides/ipresentation) インスタンスの全存続期間中ロックされ、破棄されるまで保持されます。 |

### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```


ソースは [IPresentation](../../com.aspose.slides/ipresentation) コンストラクタの実行中のみロックされます。

--------------------

If ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) が false に設定されている場合、すべての BLOB がメモリにロードされます。そうでない場合、一時ファイルなどの他の手段が使用される可能性があります。

--------------------

この動作は [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) より遅く、ソースの所有権を [IPresentation](../../com.aspose.slides/ipresentation) に渡すことが可能な場合は、[KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) の使用が推奨されます。

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


ソースは [IPresentation](../../com.aspose.slides/ipresentation) インスタンスの全存続期間中ロックされ、破棄されるまで保持されます。

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) はこの動作を使用するために true に設定する必要があり、設定されていない場合は例外がスローされます。

--------------------

この動作は推奨されます。[LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease) より高速で、メモリ使用量も少なくなります。