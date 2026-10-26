---
title: IVideoFrame
second_title: Aspose.Slides för Java API-referens
description: Representerar ett videoklipp på en bild.
type: docs
url: /sv/com.aspose.slides/ivideoframe/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Representerar ett videoklipp på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Bestämmer om en video automatiskt spolas tillbaka till början så snart filmen har spelats färdigt. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bestämmer om en video automatiskt spolas tillbaka till början så snart filmen har spelats färdigt. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestämmer om en video loopas. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestämmer om en video loopas. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestämmer om en VideoFrame är dold. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestämmer om en VideoFrame är dold. |
| [getVolume()](#getVolume--) | Returnerar eller ställer in ljudvolymen. |
| [setVolume(int value)](#setVolume-int-) | Returnerar eller ställer in ljudvolymen. |
| [getPlayMode()](#getPlayMode--) | Returnerar eller ställer in videouppspelningsläget. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returnerar eller ställer in videouppspelningsläget. |
| [getFullScreenMode()](#getFullScreenMode--) | Bestämmer om en video visas i helskärmsläge. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bestämmer om en video visas i helskärmsläge. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar eller ställer in namnet på en videofil som är länkad till en VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar eller ställer in namnet på en videofil som är länkad till en VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Returnerar eller ställer in inbäddat videoobjekt. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Returnerar eller ställer in inbäddat videoobjekt. |
| [getTrimFromStart()](#getTrimFromStart--) | Trimma start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trimma start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trimma slut [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trimma slut [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Hämtar samlingen av undertexter som är kopplade till ljudramen. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Bestämmer om en video automatiskt spolas tillbaka till början så snart filmen har spelats färdigt. Läsa/skriva boolesk.

**Returnerar:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Bestämmer om en video automatiskt spolas tillbaka till början så snart filmen har spelats färdigt. Läsa/skriva boolesk.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bestämmer om en video loopas. Läsa/skriva boolesk.

**Returnerar:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bestämmer om en video loopas. Läsa/skriva boolesk.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bestämmer om en VideoFrame är dold. Läsa/skriva boolesk.

**Returnerar:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bestämmer om en VideoFrame är dold. Läsa/skriva boolesk.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Returnerar eller ställer in ljudvolymen. Läsa/skriva [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returnerar:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Returnerar eller ställer in ljudvolymen. Läsa/skriva [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Returnerar eller ställer in videouppspelningsläget. Läsa/skriva [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Returnerar:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Returnerar eller ställer in videouppspelningsläget. Läsa/skriva [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Bestämmer om en video visas i helskärmsläge. Läsa/skriva boolesk.

**Returnerar:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Bestämmer om en video visas i helskärmsläge. Läsa/skriva boolesk.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Returnerar eller ställer in namnet på en videofil som är länkad till en VideoFrame. Läsa/skriva String.

**Returnerar:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Returnerar eller ställer in namnet på en videofil som är länkad till en VideoFrame. Läsa/skriva String.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Returnerar eller ställer in inbäddat videoobjekt. Läsa/skriva [IVideo](../../com.aspose.slides/ivideo).

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Returnerar eller ställer in inbäddat videoobjekt. Läsa/skriva [IVideo](../../com.aspose.slides/ivideo).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Trimma start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //sätt trimning starttid 1 sek
>      videoFrame.setTrimFromStart(1000f);
>      //sätt trimning sluttid 2 sek
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Trimma start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //sätt trimning starttid 1 sek
>      videoFrame.setTrimFromStart(1000f);
>      //sätt trimning sluttid 2 sek
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Trimma slut [ms]

**Returnerar:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Trimma slut [ms]

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Hämtar samlingen av undertexter som är kopplade till ljudramen. Denna egendom är endast läsning och returnerar ett [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) som innehåller alla undertextspår.

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
>              // Extraherar undertexternas binära data och sparar dem till filen
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)