---
title: FontsLoader
second_title: Aspose.Slides 的 Java API 参考
description: 用于加载用户定义的自定义字体的类。
type: docs
url: /zh/com.aspose.slides/fontsloader/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

用于加载用户定义的自定义字体的类。应在创建任何演示文稿对象之前使用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | 添加额外的文件夹以搜索字体。 |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | 从二进制数据中添加字体 |
| [getFontFolders()](#getFontFolders--) | 获取字体文件夹。 |
| [clearCache()](#clearCache--) | 释放用户定义的所有自定义字体 |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


添加额外的文件夹以搜索字体。

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // 用于搜索字体的文件夹
>  String[] folders = new String[] { dataDir };
>  // 加载自定义字体目录中的字体
>  FontsLoader.loadExternalFonts(folders);
>  // 执行一些工作并进行演示/幻灯片渲染
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // 清除字体缓存
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| directories | java.lang.String[] | 要读取额外字体的目录。 |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


从二进制数据中添加字体

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 字体数据 |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


获取字体文件夹。返回已使用 LoadExternalFonts 方法添加的文件夹以及系统字体文件夹

**返回：**
java.lang.String[] - 包含文件夹名称的数组
### clearCache() {#clearCache--}
```
public static void clearCache()
```


释放用户定义的所有自定义字体

--------------------

此方法需要清除用户定义的自定义字体缓存。