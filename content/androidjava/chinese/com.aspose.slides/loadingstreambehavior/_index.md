---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Android via Java API 参考
description: 传递给方法的 java.io.InputStream 被视为二进制大型对象 (BLOB)，请参见描述。
type: docs
url: /zh/com.aspose.slides/loadingstreambehavior/
---
**继承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

传递给方法的 java.io.InputStream 被视为二进制大型对象 (BLOB)（参见 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 说明）。此枚举的值标识在将 java.io.InputStream 传递给方法时应如何处理它。根据需求，可以做出不同的决定以提供最高效的行为。

## 字段

| 字段 | 描述 |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | 流将被读取至结束然后释放——即 |
| [KeepLocked](#KeepLocked) | 流将在 [IPresentation](../../com.aspose.slides/ipresentation) 对象内部被锁定，即 |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

流将被读取至结束然后释放——即保证此流在将来不会被 [IPresentation](../../com.aspose.slides/ipresentation) 实例使用。它可以由客户端代码关闭，或以其他任何方式使用。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // 流可以关闭，因为不再需要用于 "pres" 对象。
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
 
### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
流将在 [IPresentation](../../com.aspose.slides/ipresentation) 对象内部被锁定，即流的所有权将被转移。[IPresentation](../../com.aspose.slides/ipresentation) 对象将负责在此对象自身被释放时正确地处理流的释放。该行为在需要序列化大型 BLOB 文件（例如大型视频或音频——参见 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 说明）并希望避免将该文件加载到内存或其他性能问题时极其有用。您只需打开该文件的 java.io.FileInputStream 并将其传递给方法，选择 [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior 即可。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // You should not close the stream or interact with it in any other way, it will lead to an error in Save method.
>    // The fileStream will be used for saving, what will prevent high memory consumption
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```