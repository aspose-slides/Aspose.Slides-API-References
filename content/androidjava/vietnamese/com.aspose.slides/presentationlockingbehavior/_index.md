---
title: PresentationLockingBehavior
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho hành vi liên quan đến việc xử lý tệp nguồn hoặc java.io.InputStream khi tải và làm việc với một thể hiện của .
type: docs
url: /vi/com.aspose.slides/presentationlockingbehavior/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Mô tả hành vi liên quan đến việc xử lý nguồn [IPresentation](../../com.aspose.slides/ipresentation) (tệp hoặc java.io.InputStream) khi tải và làm việc với một thể hiện của [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Nguồn là tham số được truyền vào hàm tạo [IPresentation](../../com.aspose.slides/ipresentation). Trong ví dụ dưới đây, nguồn là tệp "pres.pptx": Đối với ví dụ này, nguồn ("pres.pptx" file) sẽ bị khóa trong suốt thời gian tồn tại của thể hiện [IPresentation](../../com.aspose.slides/ipresentation), tức là không thể bị thay đổi hoặc xóa bởi tiến trình khác.
## Trường

| Trường | Mô tả |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Nguồn sẽ bị khóa chỉ trong thời gian thực thi hàm khởi tạo [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | Nguồn sẽ bị khóa trong suốt thời gian tồn tại của thể hiện [IPresentation](../../com.aspose.slides/ipresentation), cho đến khi nó được giải phóng. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

Nguồn sẽ bị khóa chỉ trong thời gian thực thi hàm khởi tạo [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Nếu ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) được đặt là false, tất cả các BLOB sẽ được tải vào bộ nhớ. Ngược lại, có thể sử dụng các phương pháp khác như tệp tạm thời.

--------------------

Hành vi này chậm hơn so với [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), và nếu có thể chuyển quyền sở hữu của nguồn sang [IPresentation](../../com.aspose.slides/ipresentation), thì nên sử dụng [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Nguồn sẽ bị khóa trong suốt thời gian tồn tại của thể hiện [IPresentation](../../com.aspose.slides/ipresentation), cho đến khi nó được giải phóng.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) phải được đặt là true để sử dụng hành vi này, nếu không sẽ ném ra ngoại lệ.

--------------------

Hành vi này được đề xuất, nó nhanh hơn và tiêu thụ ít bộ nhớ hơn so với [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).