---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Java API Reference
description: The java.io.InputStream passed to a method is considered as a Binary Large Object BLOB see  description.
type: docs
url: /com.aspose.slides/loadingstreambehavior/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

The java.io.InputStream passed to a method is considered as a Binary Large Object (BLOB) (see [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description). Values of this enumeration identify how the java.io.InputStream should be treated when it passed to the method. Depending on the requirements, different decisions could be made to provide the most efficient behavior.
## Fields

| Field | Description |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | The stream will be read to the end and then released - i.e. it will be guaranteed that this stream will not be used by [IPresentation](../../com.aspose.slides/ipresentation) instance in the future. |
| [KeepLocked](#KeepLocked) | The stream will be locked inside the [IPresentation](../../com.aspose.slides/ipresentation) object, i.e. the ownership of the stream will be transferred. |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```


The stream will be read to the end and then released - i.e. it will be guaranteed that this stream will not be used by [IPresentation](../../com.aspose.slides/ipresentation) instance in the future. It can be closed by the client code or used in any other way.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // the stream can be closed, it's no longer needed for the "pres" object.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


The stream will be locked inside the [IPresentation](../../com.aspose.slides/ipresentation) object, i.e. the ownership of the stream will be transferred. The [IPresentation](../../com.aspose.slides/ipresentation) object will be responsible to correctly dispose the stream when this object will be disposed itself. This behavior is extremely useful when you need to serialize a large BLOB file (such as a large video or audio -see [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description) and want to prevent loading this file into memory or other performance issues. You may just open the java.io.FileInputStream for this file and pass to a method, choosing [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

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

