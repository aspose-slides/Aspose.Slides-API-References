---
title: SwfOptions
second_title: Aspose.Slides Android 版 Java API 参考
description: 提供控制演示文稿以 Swf 格式保存的选项。
type: docs
url: /zh/com.aspose.slides/swfoptions/
---
**继承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口：**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

提供控制演示文稿以 Swf 格式保存的选项。

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // 实例化一个表示演示文稿文件的 Presentation 对象
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // 保存演示文稿和批注页
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getCompressed()](#getCompressed--) | Specifies whether the generated SWF document should be compressed or not. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Specifies whether the generated SWF document should be compressed or not. |
| [getViewerIncluded()](#getViewerIncluded--) | Specifies whether the generated SWF document should include the integrated document viewer or not. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Specifies whether the generated SWF document should include the integrated document viewer or not. |
| [getShowPageBorder()](#getShowPageBorder--) | Specifies whether border around pages should be shown. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Specifies whether border around pages should be shown. |
| [getShowFullScreen()](#getShowFullScreen--) | Show/hide fullscreen button. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Show/hide fullscreen button. |
| [getShowPageStepper()](#getShowPageStepper--) | Show/hide page stepper. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Show/hide page stepper. |
| [getShowSearch()](#getShowSearch--) | Show/hide search section. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Show/hide search section. |
| [getShowTopPane()](#getShowTopPane--) | Show/hide whole top pane. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Show/hide whole top pane. |
| [getShowBottomPane()](#getShowBottomPane--) | Show/hide bottom pane. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Show/hide bottom pane. |
| [getShowLeftPane()](#getShowLeftPane--) | Show/hide left pane. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Show/hide left pane. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Start with opened left pane. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Start with opened left pane. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Enable/disable context menu. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Enable/disable context menu. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Image that will be displayed as logo in the top right corner of the viewer. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Image that will be displayed as logo in the top right corner of the viewer. |
| [getLogoLink()](#getLogoLink--) | Gets or sets the full hyperlink address for a logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Gets or sets the full hyperlink address for a logo. |
| [getJpegQuality()](#getJpegQuality--) | Specifies the quality of JPEG images. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Specifies the quality of JPEG images. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Default constructor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

指定生成的 SWF 文档是否应被压缩。默认值为 true。

**返回：**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Specifies whether the generated SWF document should be compressed or not. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Specifies whether the generated SWF document should include the integrated document viewer or not. Default is true.

**Returns:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Specifies whether the generated SWF document should include the integrated document viewer or not. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

指定是否应显示页面周围的边框。默认值为 true。

**Returns:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Specifies whether border around pages should be shown. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

显示/隐藏全屏按钮。可在 flashvars 中覆盖。默认值为 true。

**返回：**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

显示/隐藏全屏按钮。可在 flashvars 中覆盖。默认值为 true。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

显示/隐藏页面步进器。可在 flashvars 中覆盖。默认值为 true。

**返回：**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

显示/隐藏页面步进器。可在 flashvars 中覆盖。默认值为 true。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Show/hide search section. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

显示/隐藏搜索区域。可在 flashvars 中覆盖。默认值为 true。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

显示/隐藏整个顶部面板。可在 flashvars 中覆盖。默认值为 true。

**Returns:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

显示/隐藏整个顶部面板。可在 flashvars 中覆盖。默认值为 true。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

显示/隐藏底部面板。可在 flashvars 中覆盖。默认值为 true。

**返回：**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

显示/隐藏底部面板。可在 flashvars 中覆盖。默认值为 true。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

显示/隐藏左侧面板。可在 flashvars 中覆盖。默认值为 true。

**返回：**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

显示/隐藏左侧面板。可在 flashvars 中覆盖。默认值为 true。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

以打开的左侧面板开始。可在 flashvars 中覆盖。默认值为 false。

**返回：**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Start with opened left pane. Can be overridden in flashvars. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

启用/禁用上下文菜单。默认值为 true。

**返回：**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```
启用/禁用上下文菜单。默认值为 true。

**返回：**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final byte[] getLogoImageBytes()
```

将在查看器右上角显示的徽标图像。图像应为 32x64 像素的 PNG 格式，否则徽标可能显示不正常。

**Returns:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

将在查看器右上角显示的徽标图像。图像应为 32x64 像素的 PNG 格式，否则徽标可能显示不正常。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

获取或设置徽标的完整超链接地址。仅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 时才有效。

**返回：**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

获取或设置徽标的完整超链接地址。仅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 时才有效。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

指定 JPEG 图像的质量。默认值为 95。

**返回：**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```
指定 JPEG 图像的质量。默认值为 95。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```
Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). This property doesn't support assigning objects of type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)


获取或设置在导出演示文稿时幻灯片在页面上的放置模式[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。此属性不支持分配类型为[HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)的对象。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |