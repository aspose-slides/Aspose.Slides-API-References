---
title: IPptOptions
second_title: Aspose.Slides for Android 的 Java API 参考
description: 提供用于控制演示文稿以 PPT 格式保存方式的选项。
type: docs
url: /zh/com.aspose.slides/ipptoptions/
---
**所有实现的接口：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

提供可控制演示文稿以 PPT 格式保存方式的选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | 表示存储在根目录条目中的对象类 GUID（CLSID）。 |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | 表示存储在根目录条目中的对象类 GUID（CLSID）。 |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

表示存储在根目录条目中的对象类 GUID（CLSID）。可用于文档对应应用程序的 COM 激活。默认值为“64818D11-4F9B-11CF-86EA-00AA00B929E8”，对应于“Microsoft Powerpoint.Slide.8”。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// 将 CLSID 设置为 'Microsoft Powerpoint.Show.8'
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
public abstract void setRootDirectoryClsid(UUID value)

表示存储在根目录条目中的对象类 GUID（CLSID）。可用于文档对应应用程序的 COM 激活。默认值为“64818D11-4F9B-11CF-86EA-00AA00B929E8”，对应于“Microsoft Powerpoint.Slide.8”。

--------------------

Presentation pres = new Presentation();
 try {
     PptOptions pptOptions = new PptOptions();

     /// 将 CLSID 设置为 “Microsoft Powerpoint.Show.8”
     pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));

     pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
 } finally {
     if (pres != null) pres.dispose();
 }

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.UUID |  |