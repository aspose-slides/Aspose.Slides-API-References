---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: メソッドに渡される java.io.InputStream は Binary Large Object (BLOB) と見なされます。詳細は description を参照してください。
type: docs
url: /ja/com.aspose.slides/loadingstreambehavior/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

The java.io.InputStream passed to a method is considered as a Binary Large Object (BLOB) (see [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description). Values of this enumeration identify how the java.io.InputStream should be treated when it passed to the method. Depending on the requirements, different decisions could be made to provide the most efficient behavior.
## フィールド

| Field | Description |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | ストリームは最後まで読み込まれ、その後解放されます - すなわち |
| [KeepLocked](#KeepLocked) | ストリームは [IPresentation](../../com.aspose.slides/ipresentation) オブジェクト内でロックされます、すなわち |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

ストリームは最後まで読み込まれ、その後解放されます - すなわち、このストリームが将来 [IPresentation](../../com.aspose.slides/ipresentation) インスタンスによって使用されないことが保証されます。クライアントコードで閉じることも、他の方法で使用することも可能です。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // ストリームは閉じることができ、"pres" オブジェクトにはもう必要ありません。
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

ストリームは [IPresentation](../../com.aspose.slides/ipresentation) オブジェクト内でロックされます、すなわち、ストリームの所有権が移譲されます。[IPresentation](../../com.aspose.slides/ipresentation) オブジェクトは、このオブジェクトが破棄される際にストリームを正しく破棄する責任があります。この動作は、大きな BLOB ファイル（大きな動画や音声など - [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) の説明参照）をシリアライズする必要があり、メモリにロードしたりその他のパフォーマンス問題を防ぎたい場合に非常に便利です。単に java.io.FileInputStream を開いてメソッドに渡し、[KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior を選択すればよいのです。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // ストリームを閉じたり、他の方法で操作したりすべきではありません。これにより Save メソッドでエラーが発生します。
>    // fileStream は保存に使用されます。これにより大量のメモリ消費を防げます。
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
