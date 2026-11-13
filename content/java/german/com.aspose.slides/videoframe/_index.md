---
title: VideoFrame
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen Videoclip auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/videoframe/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Stellt einen Videoclip auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende gespielt wurde. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende gespielt wurde. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestimmt, ob ein Video in Schleife wiedergegeben wird. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestimmt, ob ein Video in Schleife wiedergegeben wird. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestimmt, ob ein VideoFrame ausgeblendet ist. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestimmt, ob ein VideoFrame ausgeblendet ist. |
| [getVolume()](#getVolume--) | Gibt die Audio-Lautstärke zurück oder setzt sie. |
| [setVolume(int value)](#setVolume-int-) | Gibt die Audio-Lautstärke zurück oder setzt sie. |
| [getVolumeValue()](#getVolumeValue--) | Gibt die genaue Video-Lautstärke als Prozentsatz zurück oder setzt sie. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Gibt die genaue Video-Lautstärke als Prozentsatz zurück oder setzt sie. |
| [getPlayMode()](#getPlayMode--) | Gibt den Wiedergabemodus des Videos zurück oder setzt ihn. |
| [setPlayMode(int value)](#setPlayMode-int-) | Gibt den Wiedergabemodus des Videos zurück oder setzt ihn. |
| [getFullScreenMode()](#getFullScreenMode--) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt den Namen einer Videodatei zurück, die mit einem VideoFrame verknüpft ist, oder setzt ihn. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt den Namen einer Videodatei zurück, die mit einem VideoFrame verknüpft ist, oder setzt ihn. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Gibt das eingebettete Videoobjekt zurück oder setzt es. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Gibt das eingebettete Videoobjekt zurück oder setzt es. |
| [getTrimFromStart()](#getTrimFromStart--) | Trim-Start [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Trim-Start [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Trim-Ende [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Trim-Ende [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Erhält die Sammlung von Untertiteln, die dem VideoFrame zugeordnet sind. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende gespielt wurde. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende gespielt wurde. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Bestimmt, ob ein Video in Schleife wiedergegeben wird. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Bestimmt, ob ein Video in Schleife wiedergegeben wird. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Bestimmt, ob ein VideoFrame ausgeblendet ist. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Bestimmt, ob ein VideoFrame ausgeblendet ist. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Gibt die Audio-Lautstärke zurück oder setzt sie. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Rückgabewert:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Gibt die Audio-Lautstärke zurück oder setzt sie. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Gibt die genaue Video-Lautstärke als Prozentsatz zurück oder setzt sie. Der Wert wird als Prozentsatz von 0 bis 100 angegeben. Verwenden Sie diese Eigenschaft, um Lautstärkewerte zu lesen oder zu setzen, die präziser sind als die vordefinierten Stufen, die über die \#getVolume.getVolume/\#setVolume(int).setVolume(int)-Eigenschaft verfügbar sind. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lese die aktuelle genaue Lautstärke und setze sie auf 75,5 Prozent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Gibt die genaue Video-Lautstärke als Prozentsatz zurück oder setzt sie. Der Wert wird als Prozentsatz von 0 bis 100 angegeben. Verwenden Sie diese Eigenschaft, um Lautstärkewerte zu lesen oder zu setzen, die präziser sind als die vordefinierten Stufen, die über die \#getVolume.getVolume/\#setVolume(int).setVolume(int)-Eigenschaft verfügbar sind. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lese die aktuelle genaue Lautstärke und setze sie auf 75,5 Prozent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Gibt den Wiedergabemodus des Videos zurück oder setzt ihn. Lesen/Schreiben [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Rückgabewert:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Gibt den Wiedergabemodus des Videos zurück oder setzt ihn. Lesen/Schreiben [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Gibt den Namen einer Videodatei zurück, die mit einem VideoFrame verknüpft ist, oder setzt ihn. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Gibt den Namen einer Videodatei zurück, die mit einem VideoFrame verknüpft ist, oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Gibt das eingebettete Videoobjekt zurück oder setzt es. Lesen/Schreiben [IVideo](../../com.aspose.slides/ivideo).

**Rückgabewert:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Gibt das eingebettete Videoobjekt zurück oder setzt es. Lesen/Schreiben [IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Trim-Start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //Setzt Trim-Startzeit auf 1 Sekunde
>      videoFrame.setTrimFromStart(1000f);
>      //Setzt Trim-Endzeit auf 2 Sekunden
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Trim-Start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //Setzt Trim-Startzeit auf 1 Sekunde
>      videoFrame.setTrimFromStart(1000f);
>      //Setzt Trim-Endzeit auf 2 Sekunden
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
public final float getTrimFromEnd()
```

Trim-Ende [ms]

**Rückgabewert:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Trim-Ende [ms]

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Erhält die Sammlung von Untertiteln, die dem VideoFrame zugeordnet sind. Diese Eigenschaft ist nur lesend und gibt ein [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält.

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