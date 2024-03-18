---
title: Hyperlink
second_title: Aspose.Slides for Java API Reference
description: Represents a hyperlink.
type: docs
url: /com.aspose.slides/hyperlink/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Represents a hyperlink.
## Constructors

| Constructor | Description |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Creates an instance of a hyperlink. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Creates an instance of a hyperlink which points to specific slide. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Returns a special "do nothing" hyperlink. |
| [getMedia()](#getMedia--) | Returns a special "play mediafile" hyperlink. |
| [getNextSlide()](#getNextSlide--) | Returns a hyperlink to the next slide. |
| [getPreviousSlide()](#getPreviousSlide--) | Returns a hyperlink to the previous slide. |
| [getFirstSlide()](#getFirstSlide--) | Returns a hyperlink to the first slide of the presentation. |
| [getLastSlide()](#getLastSlide--) | Returns a hyperlink to the last slide of the presentation. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Returns a hyperlink to the last viewed slide. |
| [getEndShow()](#getEndShow--) | Returns a hyperlink which ends the show. |
| [getActionType()](#getActionType--) | Returns type of Hyperlink's action. |
| [getExternalUrl()](#getExternalUrl--) | Specifies the external URL. |
| [getTargetSlide()](#getTargetSlide--) | If the Hyperlink targets specific slide returns this slide. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Represents a hyperlink that is set for this portion without regard to the actual content of the portion. |
| [getTargetFrame()](#getTargetFrame--) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. |
| [getTooltip()](#getTooltip--) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. |
| [getHistory()](#getHistory--) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| [getHighlightClick()](#getHighlightClick--) | Determines whether the hyperlink should be highlighted on click. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determines whether the hyperlink should be highlighted on click. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determines whether the sound should be stopped on hyperlink click. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determines whether the sound should be stopped on hyperlink click. |
| [getSound()](#getSound--) | Represents the playing sound of the hyperlink. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Represents the playing sound of the hyperlink. |
| [getColorSource()](#getColorSource--) | Represents the source of hyperlink color - either styles or portion format. |
| [setColorSource(int value)](#setColorSource-int-) | Represents the source of hyperlink color - either styles or portion format. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the two Hyperlink instances are equal. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determines whether the two Hyperlink instances are equal. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Tests two hyperlinks for equality. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Tests two hyperlinks for inequality. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```


Creates an instance of a hyperlink.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | Hyperlink URL. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```


Creates an instance of a hyperlink which points to specific slide. Note: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Target slide. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```


Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Source hyperlink |
| targetFrame | java.lang.String | Target frame |
| tooltip | java.lang.String | Tooltip text |
| history | boolean | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| stopSoundsOnClick | boolean | Determines whether the sound should be stopped on hyperlink click. |
| highlightClick | boolean | Determines whether the hyperlink should be highlighted on click. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```


Returns a special "do nothing" hyperlink. Read-only [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```


Returns a special "play mediafile" hyperlink. Used in AudioFrame and VideoFrame. Read-only [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```


Returns a hyperlink to the next slide. Read-only [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```


Returns a hyperlink to the previous slide. Read-only [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```


Returns a hyperlink to the first slide of the presentation. Read-only [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```


Returns a hyperlink to the last slide of the presentation. Read-only [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```


Returns a hyperlink to the last viewed slide. Read-only [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```


Returns a hyperlink which ends the show. Read-only [Hyperlink](../../com.aspose.slides/hyperlink).

**Returns:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```


Returns type of Hyperlink's action. Read-only [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Returns:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```


Specifies the external URL. Read-only String.

**Returns:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```


If the Hyperlink targets specific slide returns this slide. Read-only [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```


Represents a hyperlink that is set for this portion without regard to the actual content of the portion.

--------------------

PowerPoint behaves specifically for links and their corresponding text in a portion. It allows to create text for the hyperlink in the form of a valid URL, different from the real address of the link. In this case, when you view the link in the edit window, it will be changed to match the text portion. This property represents the original value of the hyperlink.

**Returns:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```


Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String.

**Returns:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```


Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/wite String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```


Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String.

**Returns:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```


Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```


Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean.

**Returns:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```


Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```


Determines whether the hyperlink should be highlighted on click. Read/write boolean.

**Returns:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```


Determines whether the hyperlink should be highlighted on click. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```


Determines whether the sound should be stopped on hyperlink click. Read/write boolean.

**Returns:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```


Determines whether the sound should be stopped on hyperlink click. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```


Represents the playing sound of the hyperlink. Read/write [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Get the first shape hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extract the hyperlink sound in byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```


Represents the playing sound of the hyperlink. Read/write [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Get the first shape hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extract the hyperlink sound in byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```


Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returns:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```


Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the two Hyperlink instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Hyperlink to compare with the current Hyperlink. |

**Returns:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```


Determines whether the two Hyperlink instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | The Hyperlink to compare with the current Hyperlink. |

**Returns:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```


Tests two hyperlinks for equality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Second hyperlink to be tested. |

**Returns:**
boolean - **true** if hyperlinks are equal.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```


Tests two hyperlinks for inequality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Second hyperlink to be tested. |

**Returns:**
boolean - **false** if hyperlinks are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table.

**Returns:**
int - Hash code for an URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
