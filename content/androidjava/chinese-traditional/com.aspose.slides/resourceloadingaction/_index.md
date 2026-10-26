---
title: ResourceLoadingAction
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 指定外部資源載入的模式。
type: docs
url: /zh-hant/com.aspose.slides/resourceloadingaction/
---
**繼承:** 
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

指定外部資源載入的模式。
## 欄位

| 欄位 | 說明 |
| --- | --- |
| [Default](#Default) | Aspose.Slides 將照常載入外部資源。 |
| [Skip](#Skip) | Aspose.Slides 將跳過外部資源的載入。 |
| [UserProvided](#UserProvided) | Aspose.Slides 將使用使用者在 [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) 所提供的位元組陣列作為圖像資料。 |
### Default {#Default}
```
public static final int Default
```


Aspose.Slides 將照常載入外部資源。

### Skip {#Skip}
```
public static final int Skip
```


Aspose.Slides 將跳過外部資源的載入。僅會為影像儲存沒有資料的連結。

### UserProvided {#UserProvided}
```
public static final int UserProvided
```


Aspose.Slides 將使用使用者在 [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) 所提供的位元組陣列作為圖像資料。