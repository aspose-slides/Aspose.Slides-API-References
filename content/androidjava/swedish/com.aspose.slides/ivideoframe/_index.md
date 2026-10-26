---
title: IVideoFrame
second_title: Aspose.Slides för Android via Java API-referens
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
| [getRewindVideo()](#getRewindVideo--) | Avgör om en video automatiskt spolas tillbaka till början så snart filmen har spelat färdigt. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Avgör om en video automatiskt spolas tillbaka till början så snart filmen har spelat färdigt. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Avgör om en video loopas. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Avgör om en video loopas. |
| [getHideAtShowing()](#getHideAtShowing--) | Avgör om ett VideoFrame är dolt. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Avgör om ett VideoFrame är dolt. |
| [getVolume()](#getVolume--) | Returnerar eller anger ljudvolymen. |
| [setVolume(int value)](#setVolume-int-) | Returnerar eller anger ljudvolymen. |
| [getPlayMode()](#getPlayMode--) | Returnerar eller anger videouppspelningsläget. |
| [setPlayMode(int value)](#setPlayMode-int-) | Returnerar eller anger videouppspelningsläget. |
| [getFullScreenMode()](#getFullScreenMode--) | Avgör om en video visas i helskärmsläge. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Avgör om en video visas i helskärmsläge. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar eller anger namnet på en videofil som är länkat till ett VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar eller anger namnet på en videofil som är länkat till ett VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Returnerar eller anger inbäddat videoobjekt. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Returnerar eller anger inbäddat videoobjekt. |
| [getTrimFromStart()](#getTrimFromStart--) | Trimma start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trimma start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trimma slut [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trimma slut [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Hämtar samlingen av undertexter som är associerade med ljudramen. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Avgör om en video automatiskt spolas tillbaka till början så snart filmen har spelat färdigt. Läs/skriv boolean.

**Returnerar:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Avgör om en video automatiskt spolas tillbaka till början så snart filmen har spelat färdigt. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Avgör om en video loopas. Läs/skriv boolean.

**Returnerar:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Avgör om en video loopas. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Avgör om ett VideoFrame är dolt. Läs/skriv boolean.

**Returnerar:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Avgör om ett VideoFrame är dolt. Läs/skriv boolean.

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

Avgör om en video visas i helskärmsläge. Läs/skriv boolean.

**Returnerar:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Avgör om en video visas i helskärmsläge. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Returnerar eller anger namnet på en videofil som är länkat till ett VideoFrame. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Returnerar eller anger namnet på en videofil som är länkat till ett VideoFrame. Läs/skriv String.

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
>      IVideo video = pres.getVideos().addVideo(videoData);
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
>      IVideo video = pres.getVideos().addVideo(videoData);
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

Hämtar samlingen av undertexter som är associerade med ljudramen. Den här egenskapen är skrivskyddad och returnerar ett [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) som innehåller alla undertextspår.

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
>              // Extraherar undertexternas binära data och sparar dem i filen
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