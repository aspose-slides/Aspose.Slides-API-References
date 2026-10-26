---
title: PptOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 提供控制演示文稿以 PPT 格式保存方式的选项。
type: docs
url: /zh/com.aspose.slides/pptoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

提供控制演示文稿以 PPT 格式保存方式的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## 方法

| 方法 | 描述 |
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

表示存储在根目录条目中的对象类 GUID（CLSID）。可用于文档应用程序的 COM 激活。默认值为 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，对应于 'Microsoft Powerpoint.Slide.8'。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// set CLSID to 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)

表示存储在根目录条目中的对象类 GUID（CLSID）。可用于文档应用程序的 COM 激活。默认值为 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，对应于 'Microsoft Powerpoint.Slide.8'。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// set CLSID to 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |