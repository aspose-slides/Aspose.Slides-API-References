---
title: VideoFrame
second_title: Aspose.Slides för Android via Java API-referens
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
| [getRewindVideo()](#getRewindVideo--) | Bestämmer om en video automatiskt spolas tillbaka till början så snart filmen har spelats färdigt. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bestämmer om en video automatiskt spolas tillbaka till början så snart filmen har spelats färdigt. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestämmer om en video är loopad. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestämmer om en video är loopad. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestämmer om en VideoFrame är dold. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestämmer om en VideoFrame är dold. |
| [getVolume()](#getVolume--) | Returnerar eller anger ljudvolymen. |
| [setVolume(int value)](#setVolume-int-) | Returnerar eller anger ljudvolymen. |
| [getPlayMode()](#getPlayMode--) | Returnerar eller anger videouppspelningsläget. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returnerar eller anger videouppspelningsläget. |
| [getFullScreenMode()](#getFullScreenMode--) | Bestämmer om en video visas i helskärmsläge. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bestämmer om en video visas i helskärmsläge. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar eller anger namnet på en videofil som är länkad till en VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar eller anger namnet på en videofil som är länkad till en VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Returnerar eller anger inbäddat videoobjekt. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Returnerar eller anger inbäddat videoobjekt. |
| [getTrimFromStart()](#getTrimFromStart--) | Trimma start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trimma start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trimma slut [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trimma slut [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Hämtar samlingen av undertexter som är associerade med videoramen. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```


Bestämmer om en video automatiskt spolas tillbaka till början så snart filmen har spelats färdigt. Läs/skriv boolesk.

**Returnerar:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```


Bestämmer om en video automatiskt spolas tillbaka till början så snart filmen har spelats färdigt. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


Bestämmer om en video är loopad. Läs/skriv boolesk.

**Returnerar:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


Bestämmer om en video är loopad. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


Bestämmer om en VideoFrame är dold. Läs/skriv boolesk.

**Returnerar:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


Bestämmer om en VideoFrame är dold. Läs/skriv boolesk.

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


Bestämmer om en video visas i helskärmsläge. Läs/skriv boolesk.

**Returnerar:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```


Bestämmer om en video visas i helskärmsläge. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Returnerar eller anger namnet på en videofil som är länkad till en VideoFrame. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Returnerar eller anger namnet på en videofil som är länkad till en VideoFrame. Läs/skriv String.

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


Trimma start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //sätt trimningsstarttid 1 sek
>      videoFrame.setTrimFromStart(1000f);
>      //sätt trimningssluttid 2 sek
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


Trimma start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //sätt trimningsstarttid 1 sek
>      videoFrame.setTrimFromStart(1000f);
>      //sätt trimningssluttid 2 sek
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


Trimma slut [ms]

**Returnerar:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```


Trimma slut [ms]

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```


Denna egenskap är skrivskyddad och returnerar ett [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) som innehåller alla undertextspår.

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