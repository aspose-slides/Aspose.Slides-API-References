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
| [getRewindVideo()](#getRewindVideo--) | Bestämmer om en video automatiskt spolas tillbaka till start så snart filmen har spelats färdigt. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bestämmer om en video automatiskt spolas tillbaka till start så snart filmen har spelats färdigt. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestämmer om en video är loopad. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestämmer om en video är loopad. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestämmer om en VideoFrame är dold. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestämmer om en VideoFrame är dold. |
| [getVolume()](#getVolume--) | Returnerar eller anger ljudvolymen. |
| [setVolume(int value)](#setVolume-int-) | Returnerar eller anger ljudvolymen. |
| [getVolumeValue()](#getVolumeValue--) | Returnerar eller anger den exakta videovolymen som en procentsats. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Returnerar eller anger den exakta videovolymen som en procentsats. |
| [getPlayMode()](#getPlayMode--) | Returnerar eller anger videouppspelningsläget. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returnerar eller anger videouppspelningsläget. |
| [getFullScreenMode()](#getFullScreenMode--) | Bestämmer om en video visas i helskärm. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bestämmer om en video visas i helskärm. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar eller anger namnet på en videofil som är länkat till en VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar eller anger namnet på en videofil som är länkat till en VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Returnerar eller anger inbäddat videoobjekt. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Returnerar eller anger inbäddat videoobjekt. |
| [getTrimFromStart()](#getTrimFromStart--) | Trimma start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trimma start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trimma slut [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trimma slut [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Hämtar samlingen av stängda undertexter som är associerade med ljudramen. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```


Bestämmer om en video automatiskt spolas tillbaka till start så snart filmen har spelats färdigt. Läs/skriv boolean.

**Returnerar:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```


Bestämmer om en video automatiskt spolas tillbaka till start så snart filmen har spelats färdigt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```


Bestämmer om en video är loopad. Läs/skriv boolean.

**Returnerar:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```


Bestämmer om en video är loopad. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```


Bestämmer om en VideoFrame är dold. Läs/skriv boolean.

**Returnerar:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```


Bestämmer om en VideoFrame är dold. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```


Returnerar eller anger ljudvolymen. Läs/skriv [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returnerar:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```


Returnerar eller anger ljudvolymen. Läs/skriv [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```


Returnerar eller anger den exakta videovolymen som en procentsats. Värdet uttrycks som en procentsats från 0 till 100. Använd denna egenskap för att läsa eller ange volymer som är mer precisa än de fördefinierade nivåerna som finns via Volume-egenskapen. Läs/skriv  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Läs den aktuella exakta volymen och sätt den till 75.5 procent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```


Returnerar eller anger den exakta videovolymen som en procentsats. Värdet uttrycks som en procentsats från 0 till 100. Använd denna egenskap för att läsa eller ange volymer som är mer precisa än de fördefinierade nivåerna som finns via Volume-egenskapen. Läs/skriv  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Läs den aktuella exakta volymen och sätt den till 75.5 procent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```


Returnerar eller anger videouppspelningsläget. Läs/skriv [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Returnerar:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```


Returnerar eller anger videouppspelningsläget. Läs/skriv [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```


Bestämmer om en video visas i helskärm. Läs/skriv boolean.

**Returnerar:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```


Bestämmer om en video visas i helskärm. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Returnerar eller anger namnet på en videofil som är länkat till en VideoFrame. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Returnerar eller anger namnet på en videofil som är länkat till en VideoFrame. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```


Returnerar eller anger inbäddat videoobjekt. Läs/skriv [IVideo](../../com.aspose.slides/ivideo).

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```


Returnerar eller anger inbäddat videoobjekt. Läs/skriv [IVideo](../../com.aspose.slides/ivideo).

**Parametrar:**
| Parameter | Typ | Beskrivning |
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
>      //sätt trimningsstarttid 1sek
>      videoFrame.setTrimFromStart(1000f);
>      //sätt trimningssluttid 2sek
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```


Hämtar samlingen av stängda undertexter som är associerade med ljudramen. Denna egenskap är endast läsning och returnerar en [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) som innehåller alla undertextspår.

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
>              // Extraherar den binära undertextdata och sparar den till filen
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