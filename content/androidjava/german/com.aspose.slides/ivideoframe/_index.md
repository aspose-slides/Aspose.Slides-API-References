---
title: IVideoFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getRewindVideo()](#getRewindVideo--) | Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestimmt, ob ein Video wiederholt wird. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestimmt, ob ein Video wiederholt wird. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestimmt, ob ein VideoFrame ausgeblendet ist. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestimmt, ob ein VideoFrame ausgeblendet ist. |
| [getVolume()](#getVolume--) | Liefert oder setzt die Audio-Lautstärke. |
| [setVolume(int value)](#setVolume-int-) | Liefert oder setzt die Audio-Lautstärke. |
| [getPlayMode()](#getPlayMode--) | Liefert oder setzt den Video-Wiedergabemodus. |
| [setPlayMode(int value)](#setPlayMode-int-) | Liefert oder setzt den Video-Wiedergabemodus. |
| [getFullScreenMode()](#getFullScreenMode--) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. |
| [getLinkPathLong()](#getLinkPathLong--) | Liefert oder setzt den Namen einer Videodatei, die mit einem VideoFrame verknüpft ist. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Liefert oder setzt den Namen einer Videodatei, die mit einem VideoFrame verknüpft ist. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Liefert oder setzt das eingebettete Video-Objekt. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Liefert oder setzt das eingebettete Video-Objekt. |
| [getTrimFromStart()](#getTrimFromStart--) | Trim-Start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trim-Start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trim-Ende [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trim-Ende [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Liefert die Sammlung geschlossener Untertitel, die dem Audio-Frame zugeordnet sind. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. Lese/Schreib boolesch.

**Rückgabewert:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bestimmt, ob ein Video wiederholt wird. Lese/Schreib boolesch.

**Rückgabewert:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bestimmt, ob ein Video wiederholt wird. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bestimmt, ob ein VideoFrame ausgeblendet ist. Lese/Schreib boolesch.

**Rückgabewert:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bestimmt, ob ein VideoFrame ausgeblendet ist. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Liefert oder setzt die Audio-Lautstärke. Lese/Schreib [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Rückgabewert:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Liefert oder setzt die Audio-Lautstärke. Lese/Schreib [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Liefert oder setzt den Video-Wiedergabemodus. Lese/Schreib [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Rückgabewert:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Liefert oder setzt den Video-Wiedergabemodus. Lese/Schreib [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Lese/Schreib boolesch.

**Rückgabewert:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Liefert oder setzt den Namen einer Videodatei, die mit einem VideoFrame verknüpft ist. Lese/Schreib String.

**Rückgabewert:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Liefert oder setzt den Namen einer Videodatei, die mit einem VideoFrame verknüpft ist. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Liefert oder setzt das eingebettete Video-Objekt. Lese/Schreib [IVideo](../../com.aspose.slides/ivideo).

**Rückgabewert:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Liefert oder setzt das eingebettete Video-Objekt. Lese/Schreib [IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Trim-Start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //Trim-Startzeit auf 1 Sekunde setzen
>      videoFrame.setTrimFromStart(1000f);
>      //Trim-Endzeit auf 2 Sekunden setzen
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Trim-Start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //Trim-Startzeit auf 1 Sekunde setzen
>      videoFrame.setTrimFromStart(1000f);
>      //Trim-Endzeit auf 2 Sekunden setzen
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

Trim-Ende [ms]

**Rückgabewert:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Trim-Ende [ms]

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Liefert die Sammlung geschlossener Untertitel, die dem Audio-Frame zugeordnet sind. Diese Eigenschaft ist schreibgeschützt und gibt ein [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält.

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


**Rückgabewert:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)