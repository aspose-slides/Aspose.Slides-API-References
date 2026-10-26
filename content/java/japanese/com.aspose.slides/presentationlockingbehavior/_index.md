---
title: PresentationLockingBehavior
second_title: Aspose.Slides for Java API リファレンス
description: ロード中およびインスタンスで作業する際に、ソースファイルまたは java.io.InputStream を扱う方法に関する動作を表します。
type: docs
url: /ja/com.aspose.slides/presentationlockingbehavior/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

[IPresentation](../../com.aspose.slides/ipresentation) ソース（file または java.io.InputStream）をロードし、[IPresentation](../../com.aspose.slides/ipresentation) のインスタンスで操作する際の動作を表します。

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
| [LoadAndRelease](#LoadAndRelease) | ソースは [IPresentation](../../com.aspose.slides/ipresentation) コンストラクタの実行中だけロックされます。 |
| [KeepLocked](#KeepLocked) | ソースは [IPresentation](../../com.aspose.slides/ipresentation) インスタンスの存続期間全体でロックされ、破棄されるまで保持されます。 |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

ソースは [IPresentation](../../com.aspose.slides/ipresentation) コンストラクタの実行中だけロックされます。

--------------------

もし ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) が false に設定されている場合、すべての BLOB がメモリにロードされます。そうでない場合、一時ファイルなどの他の手段が使用される可能性があります。

--------------------

この動作は [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) より遅く、ソースの所有権を [IPresentation](../../com.aspose.slides/ipresentation) に渡すことが可能な場合は [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) の使用が推奨されます。

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

ソースは [IPresentation](../../com.aspose.slides/ipresentation) インスタンスの存続期間全体でロックされ、破棄されるまで保持されます。

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) はこの動作を使用するために true に設定する必要があり、設定されていない場合は例外がスローされます。

--------------------

この動作が推奨されます。[LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease) より高速で、メモリ使用量も少なくなります。