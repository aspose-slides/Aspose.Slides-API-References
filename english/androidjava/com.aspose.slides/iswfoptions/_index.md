---
title: ISwfOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Provides options that control how a presentation is saved in SWF format.
type: docs
weight: 1057
url: /androidjava/com.aspose.slides/iswfoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Provides options that control how a presentation is saved in SWF format.
## Methods

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | Specifies whether the generated SWF document should be compressed or not. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Specifies whether the generated SWF document should be compressed or not. |
| [getViewerIncluded()](#getViewerIncluded--) | Specifies whether the generated SWF document should include the integrated document viewer or not. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Specifies whether the generated SWF document should include the integrated document viewer or not. |
| [getShowPageBorder()](#getShowPageBorder--) | Specifies whether border around pages should be shown. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Specifies whether border around pages should be shown. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
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
| [getNotesCommentsLayouting()](#getNotesCommentsLayouting--) | Provides options that control how notes and comments is placed in exported document. |
### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```


Specifies whether the generated SWF document should be compressed or not. Default is true.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```


Specifies whether the generated SWF document should be compressed or not. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```


Specifies whether the generated SWF document should include the integrated document viewer or not. Default is true.

**Returns:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```


Specifies whether the generated SWF document should include the integrated document viewer or not. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```


Specifies whether border around pages should be shown. Default is true.

**Returns:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```


Specifies whether border around pages should be shown. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```


Show/hide fullscreen button. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```


Show/hide fullscreen button. Can be overridden in flashvars. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```


Show/hide page stepper. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```


Show/hide page stepper. Can be overridden in flashvars. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```


Show/hide search section. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```


Show/hide search section. Can be overridden in flashvars. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```


Show/hide whole top pane. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```


Show/hide whole top pane. Can be overridden in flashvars. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```


Show/hide bottom pane. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```


Show/hide bottom pane. Can be overridden in flashvars. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```


Show/hide left pane. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```


Show/hide left pane. Can be overridden in flashvars. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```


Start with opened left pane. Can be overridden in flashvars. Default is false.

**Returns:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```


Start with opened left pane. Can be overridden in flashvars. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```


Enable/disable context menu. Default is true.

**Returns:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```


Enable/disable context menu. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```


Image that will be displayed as logo in the top right corner of the viewer. Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly.

**Returns:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```


Image that will be displayed as logo in the top right corner of the viewer. Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```


Gets or sets the full hyperlink address for a logo. Has an effect only if a (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) is specified.

**Returns:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```


Gets or sets the full hyperlink address for a logo. Has an effect only if a (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) is specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```


Specifies the quality of JPEG images. Default is 95.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```


Specifies the quality of JPEG images. Default is 95.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getNotesCommentsLayouting() {#getNotesCommentsLayouting--}
```
public abstract INotesCommentsLayoutingOptions getNotesCommentsLayouting()
```


Provides options that control how notes and comments is placed in exported document.

**Returns:**
[INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions)
