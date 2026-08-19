---
title: VideoFrame
second_title: Aspose.Slides för Java API-referens
description: Representerar ett videoklipp på en bild.
type: docs
url: /sv/com.aspose.slides/videoframe/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Representerar ett videoklipp på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Avgör om en video automatiskt spolas tillbaka till början så snart filmen har spelats upp. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Avgör om en video automatiskt spolas tillbaka till början så snart filmen har spelats upp. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Avgör om en video spelas i loop. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Avgör om en video spelas i loop. |
| [getHideAtShowing()](#getHideAtShowing--) | Avgör om ett VideoFrame är dolt. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Avgör om ett VideoFrame är dolt. |
| [getVolume()](#getVolume--) | Returnerar eller anger ljudvolymen. |
| [setVolume(int value)](#setVolume-int-) | Returnerar eller anger ljudvolymen. |
| [getPlayMode()](#getPlayMode--) | Returnerar eller anger videouppspelningsläget. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returnerar eller anger videouppspelningsläget. |
| [getFullScreenMode()](#getFullScreenMode--) | Avgör om en video visas i helskärmsläge. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Avgör om en video visas i helskärmsläge. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar eller anger namnet på en videofil som är länkad till ett VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar eller anger namnet på en videofil som är länkad till ett VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Returnerar eller anger inbäddat videoobjekt. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Returnerar eller anger inbäddat videoobjekt. |
| [getTrimFromStart()](#getTrimFromStart--) | Trim start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trim start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trim end [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trim end [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Hämtar samlingen av stängda bildtexter som är associerade med videoramen. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Avgör om en video automatiskt spolas tillbaka till början så snart filmen har spelats upp. Läs/skriv boolean.

**Returnerar:**
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Avgör om en video automatiskt spolas tillbaka till början så snart filmen har spelats upp. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Avgör om en video spelas i loop. Läs/skriv boolean.

**Returnerar:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Avgör om en video spelas i loop. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Avgör om ett VideoFrame är dolt. Läs/skriv boolean.

**Returnerar:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Avgör om ett VideoFrame är dolt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Returnerar eller anger ljudvolymen. Läs/skriv [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returnerar:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Returnerar eller anger ljudvolymen. Läs/skriv [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Returnerar eller anger videouppspelningsläget. Läs/skriv [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Returnerar:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Returnerar eller anger videouppspelningsläget. Läs/skriv [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Avgör om en video visas i helskärmsläge. Läs/skriv boolean.

**Returnerar:**
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Avgör om en video visas i helskärmsläge. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Returnerar eller anger namnet på en videofil som är länkad till ett VideoFrame. Läs/skriv String.

**Returnerar:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Returnerar eller anger namnet på en videofil som är länkad till ett VideoFrame. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Returnerar eller anger inbäddat videoobjekt. Läs/skriv [IVideo](../../com.aspose.slides/ivideo).

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Returnerar eller anger inbäddat videoobjekt. Läs/skriv [IVideo](../../com.aspose.slides/ivideo).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
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
>      //sätt trimningsstarttid 1sek
>      videoFrame.setTrimFromStart(1000f);
>      //sätt trimningssluttid 2sek
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
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
>      //set triming start time 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //set triming end time 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Trim end [ms]

**Returnerar:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Trim end [ms]

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Hämtar samlingen av stängda bildtexter som är associerade med videoramen. Denna egenskap är endast läsbar och returnerar ett [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) som innehåller alla bildtextspår.

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
>              // Extraherar bildtextens binära data och sparar dem till filen
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