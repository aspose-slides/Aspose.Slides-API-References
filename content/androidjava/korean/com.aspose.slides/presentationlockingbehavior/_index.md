---
title: PresentationLockingBehavior
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 인스턴스를 로드하고 작업하는 동안  소스 파일 또는  java.io.InputStream을 처리하는 동작을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/presentationlockingbehavior/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

인스턴스 [IPresentation](../../com.aspose.slides/ipresentation)를 로드하고 작업하는 동안 [IPresentation](../../com.aspose.slides/ipresentation) 소스(파일 또는 java.io.InputStream)를 처리하는 동작을 나타냅니다.

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

소스는 [IPresentation](../../com.aspose.slides/ipresentation) 생성자에 전달되는 매개변수입니다. 아래 예제에서는 소스가 "pres.pptx" 파일입니다. 이 예제에서는 소스("pres.pptx" 파일)가 [IPresentation](../../com.aspose.slides/ipresentation) 인스턴스 수명 동안 잠기게 되며, 즉 다른 프로세스에서 변경하거나 삭제할 수 없습니다.
## 필드

| Field | Description |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | 소스는 [IPresentation](../../com.aspose.slides/ipresentation) 생성자 실행 시간 동안만 잠깁니다. |
| [KeepLocked](#KeepLocked) | 소스는 [IPresentation](../../com.aspose.slides/ipresentation) 인스턴스가 폐기될 때까지 전체 수명 동안 잠깁니다. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```


소스는 [IPresentation](../../com.aspose.slides/ipresentation) 생성자 실행 시간 동안만 잠깁니다.

--------------------

([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-))가 false로 설정되면 모든 BLOB이 메모리로 로드됩니다. 그렇지 않으면 임시 파일과 같은 다른 방법이 사용될 수 있습니다.

--------------------

이 동작은 [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked)보다 느리며, 소스의 소유권을 [IPresentation](../../com.aspose.slides/ipresentation)에 전달할 수 있는 경우 [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked)를 사용하는 것이 권장됩니다.

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


소스는 [IPresentation](../../com.aspose.slides/ipresentation) 인스턴스가 폐기될 때까지 전체 수명 동안 잠깁니다.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-))는 이 동작을 사용하려면 true로 설정해야 하며, 그렇지 않으면 예외가 발생합니다.

--------------------

이 동작은 권장되며, [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease)보다 빠르고 메모리 사용량이 적습니다.