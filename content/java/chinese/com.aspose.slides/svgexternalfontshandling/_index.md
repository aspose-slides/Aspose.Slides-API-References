---
title: SvgExternalFontsHandling
second_title: Aspose.Slides for Java API 参考
description: 表示一种处理用于文本绘制的外部字体的方式。
type: docs
url: /zh/com.aspose.slides/svgexternalfontshandling/
---
**继承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SvgExternalFontsHandling extends System.Enum
```

表示一种处理文本绘制使用的外部字体的方式。
## 字段

| Field | Description |
| --- | --- |
| [AddLinksToFontFiles](#AddLinksToFontFiles) | 向 SVG 文件的 style 部分添加指向单独字体文件的链接。 |
| [Embed](#Embed) | 将字体数据直接保存到 SVG 文件。 |
| [Vectorize](#Vectorize) | 将所有使用外部字体的文本保存为图形。 |
### AddLinksToFontFiles {#AddLinksToFontFiles}
```
public static final int AddLinksToFontFiles
```

向 SVG 文件的 style 部分添加指向单独字体文件的链接。

### Embed {#Embed}
```
public static final int Embed
```

将字体数据直接保存到 SVG 文件。在使用此选项之前，请检查所有外部字体的许可证协议。

### Vectorize {#Vectorize}
```
public static final int Vectorize
```

将所有使用外部字体的文本保存为图形。