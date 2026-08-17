---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Java API リファレンス
description: メソッドに渡される java.io.InputStream は Binary Large Object (BLOB) とみなされます。詳細は description を参照してください。
type: docs
url: /ja/com.aspose.slides/loadingstreambehavior/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

メソッドに渡される java.io.InputStream は Binary Large Object (BLOB) とみなされます ([IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) の説明を参照)。この列挙体の値は、java.io.InputStream がメソッドに渡されたときにどのように扱われるかを示します。要件に応じて、最も効率的な動作を提供するためにさまざまな決定が行われる可能性があります。
## フィールド

| Field | Description |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | ストリームは最後まで読み取られ、その後解放されます - すなわち |
| [KeepLocked](#KeepLocked) | ストリームは [IPresentation](../../com.aspose.slides/ipresentation) オブジェクトの内部でロックされます、すなわち |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

ストリームは最後まで読み取られ、その後解放されます - すなわち、このストリームが将来的に [IPresentation](../../com.aspose.slides/ipresentation) インスタンスによって使用されないことが保証されます。クライアントコードによって閉じることも、他の方法で使用することも可能です。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // ストリームは閉じることができ、"pres" オブジェクトではもう必要ありません。
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

ストリームは [IPresentation](../../com.aspose.slides/ipresentation) オブジェクトの内部でロックされます、すなわちストリームの所有権が移譲されます。[IPresentation](../../com.aspose.slides/ipresentation) オブジェクトは、このオブジェクトが破棄される際にストリームを適切に破棄する責任があります。この動作は、大容量の BLOB ファイル（大きなビデオやオーディオなど - [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) の説明を参照）をシリアライズする必要があり、メモリへのロードやその他のパフォーマンス問題を防ぎたい場合に非常に有用です。単にそのファイル用に java.io.FileInputStream を開き、[KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior を選択してメソッドに渡すだけです。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // ストリームを閉じるべきではなく、他の方法で操作してはいけません。これにより Save メソッドでエラーが発生します。
>    // fileStream は保存に使用され、高いメモリ消費を防ぎます
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
