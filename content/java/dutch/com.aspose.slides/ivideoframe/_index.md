---
title: IVideoFrame
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een video-clip op een dia voor.
type: docs
url: /nl/com.aspose.slides/ivideoframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Stelt een video-clip op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bepaalt of een video wordt herhaald. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bepaalt of een video wordt herhaald. |
| [getHideAtShowing()](#getHideAtShowing--) | Bepaalt of een VideoFrame verborgen is. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bepaalt of een VideoFrame verborgen is. |
| [getVolume()](#getVolume--) | Geeft of stelt het audio-volume in. |
| [setVolume(int value)](#setVolume-int-) | Geeft of stelt het audio-volume in. |
| [getPlayMode()](#getPlayMode--) | Geeft of stelt de video-afspeelmodus in. |
| [setPlayMode(int value)](#setPlayMode-int-) | Geeft of stelt de video-afspeelmodus in. |
| [getFullScreenMode()](#getFullScreenMode--) | Bepaalt of een video wordt weergegeven in volledigschermmodus. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bepaalt of een video wordt weergegeven in volledigschermmodus. |
| [getLinkPathLong()](#getLinkPathLong--) | Geeft of stelt de naam van een videobestand in dat gekoppeld is aan een VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Geeft of stelt de naam van een videobestand in dat gekoppeld is aan een VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Geeft of stelt het ingebedde video-object in. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Geeft of stelt het ingebedde video-object in. |
| [getTrimFromStart()](#getTrimFromStart--) | Trim start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trim start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trim end [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trim end [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Haalt de verzameling gesloten bijschriften op die bij het audiokader horen. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bepaalt of een video wordt herhaald. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bepaalt of een video wordt herhaald. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bepaalt of een VideoFrame verborgen is. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bepaalt of een VideoFrame verborgen is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Geeft of stelt het audio-volume in. Lezen/schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retourneert:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Geeft of stelt het audio-volume in. Lezen/schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Geeft of stelt de video-afspeelmodus in. Lezen/schrijven [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Retourneert:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Geeft of stelt de video-afspeelmodus in. Lezen/schrijven [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Bepaalt of een video wordt weergegeven in volledigschermmodus. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Bepaalt of een video wordt weergegeven in volledigschermmodus. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Geeft of stelt de naam van een videobestand in dat gekoppeld is aan een VideoFrame. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Geeft of stelt de naam van een videobestand in dat gekoppeld is aan een VideoFrame. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Geeft of stelt het ingebedde video-object in. Lezen/schrijven [IVideo](../../com.aspose.slides/ivideo).

**Retourneert:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Geeft of stelt het ingebedde video-object in. Lezen/schrijven [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Trim start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //stel trim starttijd in op 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //stel trim eindtijd in op 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Trim start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //stel trim starttijd in op 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //stel trim eindtijd in op 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Trim end [ms]

**Retourneert:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Trim end [ms]

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Haalt de verzameling gesloten bijschriften op die bij het audiokader horen. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) met alle ondertitelsporen.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (!(shape instanceof IVideoFrame))
>              continue;
>          IVideoFrame videoFrame = (IVideoFrame) shape;
>          for (ICaptions captionTrack : videoFrame.getCaptionTracks())
>          {
>              // Haalt de binaire ondertitelgegevens op en slaat ze op in het bestand
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)