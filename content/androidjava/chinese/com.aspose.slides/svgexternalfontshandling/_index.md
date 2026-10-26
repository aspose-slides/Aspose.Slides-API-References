---
title: SvgExternalFontsHandling
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示处理用于文本绘制的外部字体的方式。
type: docs
url: /zh/com.aspose.slides/svgexternalfontshandling/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SvgExternalFontsHandling extends System.Enum
```

表示处理用于文本绘制的外部字体的方式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [AddLinksToFontFiles](#AddLinksToFontFiles) | 将链接添加到 SVG 文件的 style 部分，以指向单独的字体文件。 |
| [Embed](#Embed) | 将字体数据直接保存到 SVG 文件中。 |
| [Vectorize](#Vectorize) | 将使用外部字体的所有文本保存为图形。 |
### AddLinksToFontFiles {#AddLinksToFontFiles}
```
public static final int AddLinksToFontFiles
```

将链接添加到 SVG 文件的 style 部分，以指向单独的字体文件。

### Embed {#Embed}
```
public static final int Embed
```

将字体数据直接保存到 SVG 文件中。使用此选项前请检查所有外部字体的许可协议。

### Vectorize {#Vectorize}
```
public static final int Vectorize
```

将使用外部字体的所有文本保存为图形。