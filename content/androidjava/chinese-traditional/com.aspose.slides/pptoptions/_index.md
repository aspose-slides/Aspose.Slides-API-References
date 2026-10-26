---
title: PptOptions
second_title: Aspose.Slides for Android 的 Java API 參考
description: 提供控制簡報以 PPT 格式儲存方式的選項。
type: docs
url: /zh-hant/com.aspose.slides/pptoptions/
---
**繼承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有已實作的介面：**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

提供控制簡報以 PPT 格式儲存方式的選項。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Represents the object class GUID (CLSID) that is stored in the root directory entry. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Represents the object class GUID (CLSID) that is stored in the root directory entry. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


表示儲存在根目錄條目中的物件類別 GUID (CLSID)。可用於文件應用程式的 COM 啟動。預設值為 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，對應於 'Microsoft Powerpoint.Slide.8'。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// 設定 CLSID 為 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回值：**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


表示儲存在根目錄條目中的物件類別 GUID (CLSID)。可用於文件應用程式的 COM 啟動。預設值為 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，對應於 'Microsoft Powerpoint.Slide.8'。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// 設定 CLSID 為 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.UUID |  |