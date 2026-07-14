---
title: LoadingStreamBehavior
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 메서드에 전달되는 java.io.InputStream은 바이너리 대용량 객체(BLOB)로 간주됩니다. 설명을 참조하십시오.
type: docs
url: /ko/com.aspose.slides/loadingstreambehavior/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream이 메서드에 전달될 때는 바이너리 대용량 객체(BLOB)로 간주됩니다 ([IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 설명을 참조). 이 열거형의 값은 java.io.InputStream이 메서드에 전달될 때 어떻게 처리되어야 하는지를 지정합니다. 요구 사항에 따라 가장 효율적인 동작을 제공하도록 다양한 결정을 내릴 수 있습니다.

## 필드

| 필드 | 설명 |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | 스트림은 끝까지 읽힌 다음 해제됩니다 - 즉 |
| [KeepLocked](#KeepLocked) | 스트림은 [IPresentation](../../com.aspose.slides/ipresentation) 객체 내부에 잠깁니다 - 즉 |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

스트림은 끝까지 읽힌 다음 해제됩니다 - 즉 이 스트림이 앞으로 [IPresentation](../../com.aspose.slides/ipresentation) 인스턴스에 의해 사용되지 않음이 보장됩니다. 클라이언트 코드에 의해 닫히거나 다른 방식으로 사용할 수 있습니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // 스트림을 닫을 수 있습니다. 이제 "pres" 객체에 필요하지 않습니다.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

스트림은 [IPresentation](../../com.aspose.slides/ipresentation) 객체 내부에 잠깁니다 - 즉 스트림의 소유권이 이전됩니다. [IPresentation](../../com.aspose.slides/ipresentation) 객체는 이 객체가 자체적으로 해제될 때 스트림을 올바르게 해제할 책임이 있습니다. 이 동작은 큰 BLOB 파일(예: 대용량 비디오 또는 오디오 -[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 설명을 참조)을 직렬화해야 하고 이 파일을 메모리로 로드하거나 기타 성능 문제를 방지하려는 경우 매우 유용합니다. 해당 파일에 대해 java.io.FileInputStream을 열고 메서드에 전달하면 [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior를 선택할 수 있습니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // 스트림을 닫거나 다른 방식으로 조작하면 안 됩니다. 이렇게 하면 Save 메서드에서 오류가 발생합니다.
>    // fileStream은 저장에 사용되며, 이는 높은 메모리 사용을 방지합니다
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```