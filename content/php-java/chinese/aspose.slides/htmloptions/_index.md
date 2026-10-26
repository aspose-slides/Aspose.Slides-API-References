---
title: HtmlOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/htmloptions/
---
## HtmlOptions 类

表示一个 HTML 导出选项。

### HtmlOptions {#HtmlOptions}

| 名称 | 描述 |
| --- | --- |
| HtmlOptions([VideoPlayerHtmlController](../videoplayerhtmlcontroller)) | 创建一个新的 HtmlOptions 对象，指定回调。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| linkEmbedController | [VideoPlayerHtmlController](../videoplayerhtmlcontroller) | 控制保存项目的回调对象。 |

**返回:**
HtmlOptions

---

### HtmlOptions {#HtmlOptions}

| 名称 | 描述 |
| --- | --- |
| HtmlOptions() | 创建一个新的 HtmlOptions 对象，用于保存为单个 HTML 文件。 |

**返回:**
HtmlOptions

---

### getDeletePicturesCroppedAreas {#getDeletePicturesCroppedAreas}

| 名称 | 描述 |
| --- | --- |
| getDeletePicturesCroppedAreas () | 一个布尔标志，指示裁剪的部分是否保留在文档中。若为 true，裁剪的部分将被移除；若为 false，它们将序列化到文档中（这可能导致文件更大）。 |

**返回:**
boolean

---

### getDisableFontLigatures {#getDisableFontLigatures}

| 名称 | 描述 |
| --- | --- |
| getDisableFontLigatures () | 获取或设置一个值，指示文本是否在渲染时不使用连字。设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 false。 |

**返回:**
boolean

---

### getHtmlFormatter {#getHtmlFormatter}

| 名称 | 描述 |
| --- | --- |
| getHtmlFormatter () | 获取或设置 HTML 模板。读/写 IHtmlFormatter。 |

**返回:**
[HtmlFormatter](../htmlformatter)

---

### getInkOptions {#getInkOptions}

| 名称 | 描述 |
| --- | --- |
| getInkOptions () | 提供控制导出文档中 Ink 对象外观的选项。只读 IInkOptions |

**返回:**
[InkOptions](../inkoptions)

---

### getJpegQuality {#getJpegQuality}

| 名称 | 描述 |
| --- | --- |
| getJpegQuality () | 获取或设置决定 PDF 文档中 JPEG 图像质量的值。读/写 byte。仅在文档包含 JPEG 图像时生效。使用此属性可在以 PDF 格式保存时获取或设置文档中图像的质量。该值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。默认值为 95。 |

**返回:**
byte

---

### getPicturesCompression {#getPicturesCompression}

| 名称 | 描述 |
| --- | --- |
| getPicturesCompression () | 表示图片压缩级别 |

**返回:**
int

---

### getShowHiddenSlides {#getShowHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| getShowHiddenSlides () | 指定生成的文档是否应包含隐藏幻灯片。默认值为 false。 |

**返回:**
boolean

---

### getSlideImageFormat {#getSlideImageFormat}

| 名称 | 描述 |
| --- | --- |
| getSlideImageFormat () | 获取或设置幻灯片图像格式选项。读/写 ISlideImageFormat。 |

**返回:**
[SlideImageFormat](../slideimageformat)

---

### getSlidesLayoutOptions {#getSlidesLayoutOptions}

| 名称 | 描述 |
| --- | --- |
| getSlidesLayoutOptions () | 获取或设置导出演示文稿时幻灯片在页面上的放置模式 ISlidesLayoutOptions。 |

**返回:**
[NotesCommentsLayoutingOptions](../notescommentslayoutingoptions), [HandoutLayoutingOptions](../handoutlayoutingoptions)

---

### getSvgResponsiveLayout {#getSvgResponsiveLayout}

| 名称 | 描述 |
| --- | --- |
| getSvgResponsiveLayout () | 若为 true，则从 svg 容器中排除宽度和高度属性——这将使布局具有响应性。若为 false，则保留。读/写 boolean。 |

**返回:**
boolean

---

### setDeletePicturesCroppedAreas {#setDeletePicturesCroppedAreas}

| 名称 | 描述 |
| --- | --- |
| setDeletePicturesCroppedAreas (boolean) | 一个布尔标志，指示裁剪的部分是否保留在文档中。若为 true，裁剪的部分将被移除；若为 false，它们将序列化到文档中（这可能导致文件更大）。 |

**返回:**
void

---

### setDisableFontLigatures {#setDisableFontLigatures}

| 名称 | 描述 |
| --- | --- |
| setDisableFontLigatures (boolean) | 获取或设置一个值，指示文本是否在渲染时不使用连字。设置为 true 时，连字将在渲染输出中被禁用。默认情况下，此属性设置为 false。 |

**返回:**
void

---

### setHtmlFormatter {#setHtmlFormatter}

| 名称 | 描述 |
| --- | --- |
| setHtmlFormatter ([HtmlFormatter](../htmlformatter)) | 获取或设置 HTML 模板。读/写 IHtmlFormatter。 |

**返回:**
void

---

### setJpegQuality {#setJpegQuality}

| 名称 | 描述 |
| --- | --- |
| setJpegQuality (byte) | 获取或设置决定 PDF 文档中 JPEG 图像质量的值。读/写 byte。仅在文档包含 JPEG 图像时生效。使用此属性可在以 PDF 格式保存时获取或设置文档中图像的质量。该值范围为 0 到 100，其中 0 表示质量最差但压缩率最高，100 表示质量最佳但压缩率最低。默认值为 95。 |

**返回:**
void

---

### setPicturesCompression {#setPicturesCompression}

| 名称 | 描述 |
| --- | --- |
| setPicturesCompression (int) | 表示图片压缩级别 |

**返回:**
void

---

### setShowHiddenSlides {#setShowHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| setShowHiddenSlides (boolean) | 指定生成的文档是否应包含隐藏幻灯片。默认值为 false。 |

**返回:**
void

---

### setSlideImageFormat {#setSlideImageFormat}

| 名称 | 描述 |
| --- | --- |
| setSlideImageFormat ([SlideImageFormat](../slideimageformat)) | 获取或设置幻灯片图像格式选项。读/写 ISlideImageFormat。 |

**返回:**
void

---

### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| 名称 | 描述 |
| --- | --- |
| setSlidesLayoutOptions ([NotesCommentsLayoutingOptions](../notescommentslayoutingoptions)) | 获取或设置导出演示文稿时幻灯片在页面上的放置模式 ISlidesLayoutOptions。 |

**返回:**
void

---

### setSlidesLayoutOptions {#setSlidesLayoutOptions}

| 名称 | 描述 |
| --- | --- |
| setSlidesLayoutOptions ([HandoutLayoutingOptions](../handoutlayoutingoptions)) | 获取或设置导出演示文稿时幻灯片在页面上的放置模式 ISlidesLayoutOptions。 |

**返回:**
void

---

### setSvgResponsiveLayout {#setSvgResponsiveLayout}

| 名称 | 描述 |
| --- | --- |
| setSvgResponsiveLayout (boolean) | 若为 true，则从 svg 容器中排除宽度和高度属性——这将使布局具有响应性。若为 false，则保留。读/写 boolean。 |

**返回:**
void

---