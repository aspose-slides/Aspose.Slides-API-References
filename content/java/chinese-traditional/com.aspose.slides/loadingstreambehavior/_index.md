---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Java API 參考文件
description: 傳遞給方法的 java.io.InputStream 被視為二進位大型物件 (BLOB)，請參閱說明。
type: docs
url: /zh-hant/com.aspose.slides/loadingstreambehavior/
---
**繼承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

傳遞給方法的 java.io.InputStream 被視為二進位大型物件 (BLOB)（請參閱 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 說明）。此列舉的值用於識別在傳遞給方法時應如何處理 java.io.InputStream。根據需求，可做出不同決策以提供最高效的行為。
## 欄位

| 欄位 | 說明 |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | 串流將被讀取至結束，然後釋放 - 即 |
| [KeepLocked](#KeepLocked) | 串流將被鎖定於 [IPresentation](../../com.aspose.slides/ipresentation) 物件內，即 |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

串流將被讀取至結束，然後釋放 - 即保證未來此串流不會被 [IPresentation](../../com.aspose.slides/ipresentation) 實例使用。它可以由客戶端程式碼關閉或以其他方式使用。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // 串流可以關閉，因為不再需要「pres」物件。
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

串流將被鎖定於 [IPresentation](../../com.aspose.slides/ipresentation) 物件內，即串流的所有權將被轉移。[IPresentation](../../com.aspose.slides/ipresentation) 物件將負責在此物件本身被釋放時正確處置串流。當您需要序列化大型 BLOB 檔案（例如大型視訊或音訊 - 請參閱 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 說明），且想避免將此檔案載入記憶體或產生其他效能問題時，此行為極為有用。您只需為此檔案開啟 java.io.FileInputStream 並傳遞給方法，選擇 [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // 您不應關閉串流或以其他任何方式與之互動，這會在 Save 方法中導致錯誤。
>    // fileStream 將用於儲存，這將防止高記憶體消耗
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
