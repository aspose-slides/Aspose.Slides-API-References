---
title: SwfOptions
second_title: Aspose.Slides Java API 参考
description: 提供控制演示文稿以 Swf 格式保存方式的选项。
type: docs
url: /zh/com.aspose.slides/swfoptions/
---
**继承:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有实现的接口:**  
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

提供控制演示文稿以 Swf 格式保存方式的选项。

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
>      // 保存演示文稿和备注页面
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | 默认构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包括隐藏的幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包括隐藏的幻灯片。 |
| [getCompressed()](#getCompressed--) | 指定生成的 SWF 文档是否应压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 指定生成的 SWF 文档是否应压缩。 |
| [getViewerIncluded()](#getViewerIncluded--) | 指定生成的 SWF 文档是否应包含集成的文档查看器。 |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | 指定生成的 SWF 文档是否应包含集成的文档查看器。 |
| [getShowPageBorder()](#getShowPageBorder--) | 指定是否显示页面周围的边框。 |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | 指定是否显示页面周围的边框。 |
| [getShowFullScreen()](#getShowFullScreen--) | 显示/隐藏全屏按钮。 |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | 显示/隐藏全屏按钮。 |
| [getShowPageStepper()](#getShowPageStepper--) | 显示/隐藏页面步进器。 |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | 显示/隐藏页面步进器。 |
| [getShowSearch()](#getShowSearch--) | 显示/隐藏搜索区域。 |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | 显示/隐藏搜索区域。 |
| [getShowTopPane()](#getShowTopPane--) | 显示/隐藏整个顶部面板。 |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | 显示/隐藏整个顶部面板。 |
| [getShowBottomPane()](#getShowBottomPane--) | 显示/隐藏底部面板。 |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | 显示/隐藏底部面板。 |
| [getShowLeftPane()](#getShowLeftPane--) | 显示/隐藏左侧面板。 |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | 显示/隐藏左侧面板。 |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | 以打开的左侧面板开始。 |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | 以打开的左侧面板开始。 |
| [getEnableContextMenu()](#getEnableContextMenu--) | 启用/禁用上下文菜单。 |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | 启用/禁用上下文菜单。 |
| [getLogoImageBytes()](#getLogoImageBytes--) | 将在查看器右上角显示为徽标的图像。 |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | 将在查看器右上角显示为徽标的图像。 |
| [getLogoLink()](#getLogoLink--) | 获取或设置徽标的完整超链接地址。 |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | 获取或设置徽标的完整超链接地址。 |
| [getJpegQuality()](#getJpegQuality--) | 指定 JPEG 图像的质量。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 指定 JPEG 图像的质量。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置导出演示文稿时幻灯片在页面上放置的模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置导出演示文稿时幻灯片在页面上放置的模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

默认构造函数。

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

指定生成的文档是否应包括隐藏的幻灯片。默认值为 false。

**返回:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包括隐藏的幻灯片。默认值为 false。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

指定生成的 SWF 文档是否应压缩。默认值为 true。

**返回:**  
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

指定生成的 SWF 文档是否应压缩。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

指定生成的 SWF 文档是否应包含集成的文档查看器。默认值为 true。

**返回:**  
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

指定生成的 SWF 文档是否应包含集成的文档查看器。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

指定是否显示页面周围的边框。默认值为 true。

**返回:**  
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

指定是否显示页面周围的边框。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

显示/隐藏全屏按钮。可在 flashvars 中覆盖。默认值为 true。

**返回:**  
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

显示/隐藏全屏按钮。可在 flashvars 中覆盖。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

显示/隐藏页面步进器。可在 flashvars 中覆盖。默认值为 true。

**返回:**  
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

显示/隐藏页面步进器。可在 flashvars 中覆盖。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

显示/隐藏搜索区域。可在 flashvars 中覆盖。默认值为 true。

**返回:**  
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

显示/隐藏搜索区域。可在 flashvars 中覆盖。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

显示/隐藏整个顶部面板。可在 flashvars 中覆盖。默认值为 true。

**返回:**  
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

显示/隐藏整个顶部面板。可在 flashvars 中覆盖。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

显示/隐藏底部面板。可在 flashvars 中覆盖。默认值为 true。

**返回:**  
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

显示/隐藏底部面板。可在 flashvars 中覆盖。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

显示/隐藏左侧面板。可在 flashvars 中覆盖。默认值为 true。

**返回:**  
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

显示/隐藏左侧面板。可在 flashvars 中覆盖。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

以打开的左侧面板开始。可在 flashvars 中覆盖。默认值为 false。

**返回:**  
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

以打开的左侧面板开始。可在 flashvars 中覆盖。默认值为 false。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

启用/禁用上下文菜单。默认值为 true。

**返回:**  
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

启用/禁用上下文菜单。默认值为 true。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

将在查看器右上角显示为徽标的图像。图像应为 32x64 像素的 PNG 图像，否则徽标可能显示不正确。

**返回:**  
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

将在查看器右上角显示为徽标的图像。图像应为 32x64 像素的 PNG 图像，否则徽标可能显示不正确。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

获取或设置徽标的完整超链接地址。仅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 时生效。

**返回:**  
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

获取或设置徽标的完整超链接地址。仅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 时生效。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

指定 JPEG 图像的质量。默认值为 95。

**返回:**  
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

指定 JPEG 图像的质量。默认值为 95。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

获取或设置导出演示文稿时幻灯片在页面上放置的模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。此属性不支持分配类型为 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 的对象。

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


**返回:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

获取或设置导出演示文稿时幻灯片在页面上放置的模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。此属性不支持分配类型为 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 的对象。

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


**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |