---
title: IVideoFrame
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Videoclip auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/ivideoframe/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Stellt einen Videoclip auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Ermittelt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Ermittelt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Ermittelt, ob ein Video in einer Schleife wiedergegeben wird. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Ermittelt, ob ein Video in einer Schleife wiedergegeben wird. |
| [getHideAtShowing()](#getHideAtShowing--) | Ermittelt, ob ein VideoFrame ausgeblendet ist. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Ermittelt, ob ein VideoFrame ausgeblendet ist. |
| [getVolume()](#getVolume--) | Gibt das Audio-Volumen zurück oder legt es fest. |
| [setVolume(int value)](#setVolume-int-) | Gibt das Audio-Volumen zurück oder legt es fest. |
| [getPlayMode()](#getPlayMode--) | Gibt den Videowiedergabemodus zurück oder legt ihn fest. |
| [setPlayMode(int value)](#setPlayMode-int-) | Gibt den Videowiedergabemodus zurück oder legt ihn fest. |
| [getFullScreenMode()](#getFullScreenMode--) | Ermittelt, ob ein Video im Vollbildmodus angezeigt wird. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Ermittelt, ob ein Video im Vollbildmodus angezeigt wird. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt den Namen einer Videodatei zurück oder legt ihn fest, die mit einem VideoFrame verknüpft ist. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt den Namen einer Videodatei zurück oder legt ihn fest, die mit einem VideoFrame verknüpft ist. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Gibt das eingebettete Videoobjekt zurück oder legt es fest. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Gibt das eingebettete Videoobjekt zurück oder legt es fest. |
| [getTrimFromStart()](#getTrimFromStart--) | Start trimmen [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Start trimmen [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | End trimmen [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | End trimmen [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Ruft die Sammlung geschlossener Untertitel ab, die dem Audio-Frame zugeordnet ist. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Ermittelt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. Lese-/Schreib-boolean.

**Rückgabe:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Ermittelt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. Lese-/Schreib-boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Ermittelt, ob ein Video in einer Schleife wiedergegeben wird. Lese-/Schreib-boolean.

**Rückgabe:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Ermittelt, ob ein Video in einer Schleife wiedergegeben wird. Lese-/Schreib-boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Ermittelt, ob ein VideoFrame ausgeblendet ist. Lese-/Schreib-boolean.

**Rückgabe:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Ermittelt, ob ein VideoFrame ausgeblendet ist. Lese-/Schreib-boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Gibt das Audio-Volumen zurück oder legt es fest. Lese-/Schreib-[AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Rückgabe:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Gibt das Audio-Volumen zurück oder legt es fest. Lese-/Schreib-[AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Gibt den Videowiedergabemodus zurück oder legt ihn fest. Lese-/Schreib-[VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Rückgabe:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Gibt den Videowiedergabemodus zurück oder legt ihn fest. Lese-/Schreib-[VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Ermittelt, ob ein Video im Vollbildmodus angezeigt wird. Lese-/Schreib-boolean.

**Rückgabe:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Ermittelt, ob ein Video im Vollbildmodus angezeigt wird. Lese-/Schreib-boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Gibt den Namen einer Videodatei zurück oder legt ihn fest, die mit einem VideoFrame verknüpft ist. Lese-/Schreib-String.

**Rückgabe:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Gibt den Namen einer Videodatei zurück oder legt ihn fest, die mit einem VideoFrame verknüpft ist. Lese-/Schreib-String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Gibt das eingebettete Videoobjekt zurück oder legt es fest. Lese-/Schreib-[IVideo](../../com.aspose.slides/ivideo).

**Rückgabe:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Gibt das eingebettete Videoobjekt zurück oder legt es fest. Lese-/Schreib-[IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Start trimmen [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //setzt die Trim-Startzeit auf 1 Sekunde
>      videoFrame.setTrimFromStart(1000f);
>      //setzt die Trim-Endzeit auf 2 Sekunden
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Start trimmen [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //setzt die Trim-Startzeit auf 1 Sekunde
>      videoFrame.setTrimFromStart(1000f);
>      //setzt die Trim-Endzeit auf 2 Sekunden
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

End trimmen [ms]

**Rückgabe:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

End trimmen [ms]

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Ruft die Sammlung geschlossener Untertitel ab, die dem Audio-Frame zugeordnet ist. Diese Eigenschaft ist schreibgeschützt und gibt ein [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält.

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
>              // Extrahiert die Binärdaten der Untertitel und speichert sie in die Datei
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)