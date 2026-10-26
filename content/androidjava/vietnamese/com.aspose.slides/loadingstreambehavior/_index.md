---
title: LoadingStreamBehavior
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: java.io.InputStream được truyền vào một phương thức được coi là một Binary Large Object (BLOB) xem mô tả.
type: docs
url: /vi/com.aspose.slides/loadingstreambehavior/
---
**Kế thừa:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream được truyền vào một phương thức được coi là một Binary Large Object (BLOB) (see [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description). Values of this enumeration identify how the java.io.InputStream should be treated when it passed to the method. Depending on the requirements, different decisions could be made to provide the most efficient behavior.
## Trường

| Trường | Mô tả |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Luồng sẽ được đọc tới cuối và sau đó được giải phóng - i.e. |
| [KeepLocked](#KeepLocked) | Luồng sẽ bị khóa bên trong đối tượng [IPresentation](../../com.aspose.slides/ipresentation), i.e. |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Luồng sẽ được đọc tới cuối và sau đó được giải phóng - i.e. sẽ được đảm bảo rằng luồng này sẽ không được sử dụng bởi thể hiện [IPresentation](../../com.aspose.slides/ipresentation) trong tương lai. Nó có thể được đóng bởi mã khách hàng hoặc được sử dụng theo bất kỳ cách nào khác.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // luồng có thể được đóng, không còn cần thiết cho đối tượng "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Luồng sẽ bị khóa bên trong đối tượng [IPresentation](../../com.aspose.slides/ipresentation), i.e. quyền sở hữu của luồng sẽ được chuyển giao. Đối tượng [IPresentation](../../com.aspose.slides/ipresentation) sẽ chịu trách nhiệm giải phóng luồng một cách đúng đắn khi đối tượng này tự nó được giải phóng. Hành vi này cực kỳ hữu ích khi bạn cần tuần tự hoá một tệp BLOB lớn (chẳng hạn một video hoặc âm thanh lớn -see [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description) và muốn ngăn việc tải tệp này vào bộ nhớ hoặc các vấn đề hiệu năng khác. Bạn chỉ cần mở java.io.FileInputStream cho tệp này và truyền vào một phương thức, chọn [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Bạn không nên đóng luồng hoặc tương tác với nó bằng bất kỳ cách nào khác, nó sẽ gây lỗi trong phương thức Save.
>    // Luồng fileStream sẽ được sử dụng để lưu, điều này sẽ ngăn ngừa tiêu thụ bộ nhớ cao
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```