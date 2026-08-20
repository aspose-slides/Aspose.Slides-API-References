---
title: SwfOptions
second_title: Aspose.Slides जावा API संदर्भ के लिए
description: प्रेजेंटेशन को Swf फॉर्मेट में सहेजा जाने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/swfoptions/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Provides options that control how a presentation is saved in Swf format.

--------------------

> ```
> निम्न उदाहरण दिखाता है कि कैसे PowerPoint को SWF Flash में परिवर्तित किया जाए।
>  
>  // एक Presentation ऑब्जेक्ट बनाएँ जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है।
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // प्रस्तुति और नोट्स पृष्ठों को सहेजना।
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## निर्माता

| Constructor | Description |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Default constructor. |
## विधियाँ

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


डिफ़ॉल्ट निर्माता।

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**रिटर्न:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


Specifies whether the generated SWF document should be compressed or not. Default is true.

**रिटर्न:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


Specifies whether the generated SWF document should be compressed or not. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


Specifies whether the generated SWF document should include the integrated document viewer or not. Default is true.

**रिटर्न:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


Specifies whether the generated SWF document should include the integrated document viewer or not. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


Specifies whether border around pages should be shown. Default is true.

**रिटर्न:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


Specifies whether border around pages should be shown. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


Show/hide fullscreen button. Can be overridden in flashvars. Default is true.

**रिटर्न:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


Show/hide fullscreen button. Can be overridden in flashvars. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


Show/hide page stepper. Can be overridden in flashvars. Default is true.

**रिटर्न:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


Show/hide page stepper. Can be overridden in flashvars. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


Show/hide search section. Can be overridden in flashvars. Default is true.

**रिटर्न:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


Show/hide search section. Can be overridden in flashvars. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


Show/hide whole top pane. Can be overridden in flashvars. Default is true.

**रिटर्न:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


Show/hide whole top pane. Can be overridden in flashvars. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


Show/hide bottom pane. Can be overridden in flashvars. Default is true.

**रिटर्न:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


Show/hide bottom pane. Can be overridden in flashvars. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


Show/hide left pane. Can be overridden in flashvars. Default is true.

**रिटर्न:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


Show/hide left pane. Can be overridden in flashvars. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


Start with opened left pane. Can be overridden in flashvars. Default is false.

**रिटर्न:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


Start with opened left pane. Can be overridden in flashvars. Default is false.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


Enable/disable context menu. Default is true.

**रिटर्न:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


Enable/disable context menu. Default is true.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


Image that will be displayed as logo in the top right corner of the viewer. Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly.

**रिटर्न:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


Image that will be displayed as logo in the top right corner of the viewer. Image should be 32x64 pixels PNG image, otherwise logo can be displayed improperly.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


Gets or sets the full hyperlink address for a logo. Has an effect only if a (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) is specified.

**रिटर्न:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


Gets or sets the full hyperlink address for a logo. Has an effect only if a (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) is specified.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Specifies the quality of JPEG images. Default is 95.

**रिटर्न:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Specifies the quality of JPEG images. Default is 95.

**पैरामीटर:**
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

**रिटर्न:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). This property doesn't support assigning objects of type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

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

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |