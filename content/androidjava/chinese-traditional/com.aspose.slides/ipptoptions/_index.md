---
title: IPptOptions
second_title: Aspose.Slides for Android via Java API 參考文件
description: 提供控制簡報以 PPT 格式儲存的選項。
type: docs
url: /zh-hant/com.aspose.slides/ipptoptions/
---
**已實作的介面：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

提供控制簡報以 PPT 格式儲存的選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | 表示儲存在根目錄項目的物件類別 GUID (CLSID)。 |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | 表示儲存在根目錄項目的物件類別 GUID (CLSID)。 |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

表示儲存在根目錄項目的物件類別 GUID (CLSID)。可用於文件應用程式的 COM 啟動。預設值為 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，對應於 'Microsoft Powerpoint.Slide.8'。

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


**返回：**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

表示儲存在根目錄項目的物件類別 GUID (CLSID)。可用於文件應用程式的 COM 啟動。預設值為 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，對應於 'Microsoft Powerpoint.Slide.8'。

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