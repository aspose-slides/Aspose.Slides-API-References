---
title: ISwfOptions
second_title: Aspose.Slides Android 版 Java API 参考
description: 提供控制演示文稿以 SWF 格式保存的选项。
type: docs
url: /zh/com.aspose.slides/iswfoptions/
---
**所有已实现的接口：**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

提供控制演示文稿以 SWF 格式保存的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 指定生成的 SWF 文档是否应压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 指定生成的 SWF 文档是否应压缩。 |
| [getViewerIncluded()](#getViewerIncluded--) | 指定生成的 SWF 文档是否应包含集成的文档查看器。 |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | 指定生成的 SWF 文档是否应包含集成的文档查看器。 |
| [getShowPageBorder()](#getShowPageBorder--) | 指定是否显示页面周围的边框。 |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | 指定是否显示页面周围的边框。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否应包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否应包含隐藏幻灯片。 |
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
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | 启动时左侧面板已打开。 |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | 启动时左侧面板已打开。 |
| [getEnableContextMenu()](#getEnableContextMenu--) | 启用/禁用上下文菜单。 |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | 启用/禁用上下文菜单。 |
| [getLogoImageBytes()](#getLogoImageBytes--) | 将在查看器右上角显示为标志的图像。 |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | 将在查看器右上角显示为标志的图像。 |
| [getLogoLink()](#getLogoLink--) | 获取或设置标志的完整超链接地址。 |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | 获取或设置标志的完整超链接地址。 |
| [getJpegQuality()](#getJpegQuality--) | 指定 JPEG 图像的质量。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | 指定 JPEG 图像的质量。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

指定生成的 SWF 文档是否应压缩。默认值为 true。

**返回值:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

指定生成的 SWF 文档是否应压缩。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

指定生成的 SWF 文档是否应包含集成的文档查看器。默认值为 true。

**返回值:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

指定生成的 SWF 文档是否应包含集成的文档查看器。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

指定是否显示页面周围的边框。默认值为 true。

**返回值:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

指定是否显示页面周围的边框。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**返回值:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

指定生成的文档是否应包含隐藏幻灯片。默认值为 false。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

显示/隐藏全屏按钮。可通过 flashvars 覆盖。默认值为 true。

**返回值:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

显示/隐藏全屏按钮。可通过 flashvars 覆盖。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

显示/隐藏页面步进器。可通过 flashvars 覆盖。默认值为 true。

**返回值:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

显示/隐藏页面步进器。可通过 flashvars 覆盖。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

显示/隐藏搜索区域。可通过 flashvars 覆盖。默认值为 true。

**返回值:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

显示/隐藏搜索区域。可通过 flashvars 覆盖。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

显示/隐藏整个顶部面板。可通过 flashvars 覆盖。默认值为 true。

**返回值:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

显示/隐藏整个顶部面板。可通过 flashvars 覆盖。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

显示/隐藏底部面板。可通过 flashvars 覆盖。默认值为 true。

**返回值:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

显示/隐藏底部面板。可通过 flashvars 覆盖。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

显示/隐藏左侧面板。可通过 flashvars 覆盖。默认值为 true。

**返回值:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

显示/隐藏左侧面板。可通过 flashvars 覆盖。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

启动时左侧面板已打开。可通过 flashvars 覆盖。默认值为 false。

**返回值:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

启动时左侧面板已打开。可通过 flashvars 覆盖。默认值为 false。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

启用/禁用上下文菜单。默认值为 true。

**返回值:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

启用/禁用上下文菜单。默认值为 true。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

将在查看器右上角显示为标志的图像。图像应为 32x64 像素的 PNG，否则标志可能显示不正确。

**返回值:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

将在查看器右上角显示为标志的图像。图像应为 32x64 像素的 PNG，否则标志可能显示不正确。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

获取或设置标志的完整超链接地址。仅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 时生效。

**返回值:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

获取或设置标志的完整超链接地址。仅在指定 (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) 时生效。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

指定 JPEG 图像的质量。默认值为 95。

**返回值:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

指定 JPEG 图像的质量。默认值为 95。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。此属性不支持分配类型为 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 的对象。

--------------------

> ```
> 示例：
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)

获取或设置导出演示文稿时幻灯片在页面上的布局模式 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。此属性不支持分配类型为 [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 的对象。

--------------------

Example:

Presentation pres = new Presentation("pres.pptx");
try {
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.setCommentsPosition(CommentsPositions.Right);

    SwfOptions options = new SwfOptions();
    options.setSlidesLayoutOptions(notesOptions);

    pres.save("pres.swf", SaveFormat.Swf, options);
} finally {
    if (pres != null) pres.dispose();
}

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |