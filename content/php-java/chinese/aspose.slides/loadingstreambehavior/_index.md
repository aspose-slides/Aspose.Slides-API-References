---
title: LoadingStreamBehavior
second_title: Aspose.Sildes 用于 PHP 的 Java API 参考
description: 
type: docs
url: /zh/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior 类

 方法接受的 java.io.InputStream 被视为二进制大对象（BLOB）（参见 IBlobManagementOptions 描述）。此枚举的取值标识在将 java.io.InputStream 传递给方法时应如何处理它。根据需求，可以做出不同的决定以提供最高效的行为。

## 常量

| 名称 | 值 | 描述 |
| --- | --- | --- |
[ReadStreamAndRelease](#ReadStreamAndRelease) | 0 | 该流将被读取至结束后释放，即保证此流在将来不会被 IPresentation 实例使用。它可以被客户端代码关闭或以任何其他方式使用。Presentation pres = new Presentation(); try { FileInputStream fileStream = new FileInputStream(new File("video.avi")); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease); fileStream.close(); // the stream can be closed, it's no longer needed for the "pres" object. } finally { if (pres != null) pres.dispose(); } |
[KeepLocked](#KeepLocked) | 1 | 该流将在 IPPresentation 对象内部被锁定，即流的所有权将被转移。IPresentation 对象将在自身被释放时负责正确处置该流。此行为在需要序列化大型 BLOB 文件（例如大型视频或音频 -see IBlobManagementOptions description）并希望避免将该文件加载到内存或其他性能问题时极其有用。您可以仅打开该文件的 java.io.FileInputStream 并传递给方法，选择 LoadingStreamBehavior#KeepLocked LoadingStreamBehavior。Presentation pres = new Presentation(); try { FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked); // fileStream.close(); // You should not close the stream or interact with it in any other way, it will lead to an error in Save method. // The fileStream will be used for saving, what will prevent high memory consumption pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx); } finally { if (pres != null) pres.dispose(); } |

---

### ReadStreamAndRelease {#ReadStreamAndRelease}
该流将被读取至结束后释放，即保证此流在将来不会被 IPresentation 实例使用。它可以被客户端代码关闭或以任何其他方式使用。Presentation pres = new Presentation(); try { FileInputStream fileStream = new FileInputStream(new File("video.avi")); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease); fileStream.close(); // the stream can be closed, it's no longer needed for the "pres" object. } finally { if (pres != null) pres.dispose(); }

---

### KeepLocked {#KeepLocked}
该流将在 IPPresentation 对象内部被锁定，即流的所有权将被转移。IPresentation 对象将在自身被释放时负责正确处置该流。此行为在需要序列化大型 BLOB 文件（例如大型视频或音频 -see IBlobManagementOptions description）并希望避免将该文件加载到内存或其他性能问题时极其有用。您可以仅打开该文件的 java.io.FileInputStream 并传递给方法，选择 LoadingStreamBehavior#KeepLocked LoadingStreamBehavior。Presentation pres = new Presentation(); try { FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open); pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked); // fileStream.close(); // You should not close the stream or interact with it in any other way, it will lead to an error in Save method. // The fileStream will be used for saving, what will prevent high memory consumption pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx); } finally { if (pres != null) pres.dispose(); }

---