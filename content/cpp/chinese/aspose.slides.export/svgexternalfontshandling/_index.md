---
title: SvgExternalFontsHandling
second_title: Aspose.Slides C++ API 参考
description: 表示处理用于文本绘制的外部字体的方式。
type: docs
weight: 1080
url: /zh/aspose.slides.export/svgexternalfontshandling/
---
## SvgExternalFontsHandling 枚举


表示处理用于文本绘制的外部字体的方式。

```cpp
enum class SvgExternalFontsHandling
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| AddLinksToFontFiles | 0 | 在 SVG 文件的 style 部分添加指向单独字体文件的链接。 |
| Embed | 1 | 将字体数据直接保存到 SVG 文件中。在使用此选项前，请检查所有外部字体的许可协议。 |
| Vectorize | 2 | 将使用外部字体的所有文本保存为图形。 |

## 另请参见

* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)