---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a hyperlink.
type: docs
url: /com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Represents a hyperlink.
## Methods

| Method | Description |
| --- | --- |
| [getActionType()](#getActionType--) | Returns type of HyperLinkEx's action. |
| [getExternalUrl()](#getExternalUrl--) | Specifies the external URL If this property become not null then property TargetSlide become null. |
| [getTargetSlide()](#getTargetSlide--) | If the HyperlinkEx targets specific slide returns this slide. |
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
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determines whether the two Hyperlink instances are equal. |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


Returns type of HyperLinkEx's action. Read-only [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Returns:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


Specifies the external URL If this property become not null then property TargetSlide become null. Read-only String.

**Returns:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


If the HyperlinkEx targets specific slide returns this slide. If the property become not null then property ExternalUrl become null. Read-only [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/write String.

**Returns:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String.

**Returns:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean.

**Returns:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```


Determines whether the hyperlink should be highlighted on click. Read/write boolean.

**Returns:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```


Determines whether the hyperlink should be highlighted on click. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```


Determines whether the sound should be stopped on hyperlink click. Read/write boolean.

**Returns:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


Determines whether the sound should be stopped on hyperlink click. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
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
public abstract void setSound(IAudio value)
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
public abstract int getColorSource()
```


Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returns:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```


Determines whether the two Hyperlink instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | The Hyperlink to compare with the current Hyperlink. |

**Returns:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
