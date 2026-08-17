---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Java API 参考
description: 传递给方法的 java.io.InputStream 被视为二进制大对象（BLOB），请参见描述。
type: docs
url: /zh/com.aspose.slides/loadingstreambehavior/
---
**继承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

传递给方法的 java.io.InputStream 被视为二进制大对象（BLOB）（参见 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 描述）。此枚举的值标识在将 java.io.InputStream 传递给方法时应如何处理它。根据需求，可以做出不同的决定以提供最高效的行为。

## 字段

| 字段 | 描述 |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | 流将被读取至结束然后释放 - 即 |
| [KeepLocked](#KeepLocked) | 流将在 [IPresentation](../../com.aspose.slides/ipresentation) 对象内部被锁定，即 |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

流将被读取至结束然后释放 - 即 确保此流在将来不会被 [IPresentation](../../com.aspose.slides/ipresentation) 实例使用。它可以被客户端代码关闭或以其他任何方式使用。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // 此流可以关闭，因为对 "pres" 对象不再需要它。
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

流将在 [IPresentation](../../com.aspose.slides/ipresentation) 对象内部被锁定，即 流的所有权将被转移。[IPresentation](../../com.aspose.slides/ipresentation) 对象将在该对象自身被释放时负责正确释放流。当需要序列化大型 BLOB 文件（例如大型视频或音频 - 参见 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 描述）并希望防止将此文件加载到内存或其他性能问题时，此行为极其有用。您可以仅打开该文件的 java.io.FileInputStream 并传递给方法，选择 [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // 您不应关闭流或以任何其他方式与其交互，这将在 Save 方法中导致错误。
>    // fileStream 将用于保存，这将防止高内存消耗
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```