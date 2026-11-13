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
| [getRewindVideo()](#getRewindVideo--) | Bestimmt, ob ein Video automatisch zum Anfang zurückgespult wird, sobald der Film die Wiedergabe beendet hat. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bestimmt, ob ein Video automatisch zum Anfang zurückgespult wird, sobald der Film die Wiedergabe beendet hat. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestimmt, ob ein Video wiederholt wird. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestimmt, ob ein Video wiederholt wird. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestimmt, ob ein VideoFrame ausgeblendet ist. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestimmt, ob ein VideoFrame ausgeblendet ist. |
| [getVolume()](#getVolume--) | Liefert oder legt die Audio-Lautstärke fest. |
| [setVolume(int value)](#setVolume-int-) | Liefert oder legt die Audio-Lautstärke fest. |
| [getVolumeValue()](#getVolumeValue--) | Liefert oder legt die genaue Video-Lautstärke als Prozentsatz fest. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Liefert oder legt die genaue Video-Lautstärke als Prozentsatz fest. |
| [getPlayMode()](#getPlayMode--) | Liefert oder legt den Wiedergabemodus des Videos fest. |
| [setPlayMode(int value)](#setPlayMode-int-) | Liefert oder legt den Wiedergabemodus des Videos fest. |
| [getFullScreenMode()](#getFullScreenMode--) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. |
| [getLinkPathLong()](#getLinkPathLong--) | Liefert oder legt den Namen einer an ein VideoFrame verknüpften Videodatei fest. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Liefert oder legt den Namen einer an ein VideoFrame verknüpften Videodatei fest. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Liefert oder legt eingebettetes Videoobjekt fest. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Liefert oder legt eingebettetes Videoobjekt fest. |
| [getTrimFromStart()](#getTrimFromStart--) | Start zuschneiden [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Start zuschneiden [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Ende zuschneiden [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Ende zuschneiden [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Liefert die Sammlung geschlossener Untertitel, die dem Audio-Frame zugeordnet sind. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Bestimmt, ob ein Video automatisch zum Anfang zurückgespult wird, sobald der Film die Wiedergabe beendet hat. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Bestimmt, ob ein Video automatisch zum Anfang zurückgespult wird, sobald der Film die Wiedergabe beendet hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bestimmt, ob ein Video wiederholt wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bestimmt, ob ein Video wiederholt wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bestimmt, ob ein VideoFrame ausgeblendet ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bestimmt, ob ein VideoFrame ausgeblendet ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Liefert oder legt die Audio-Lautstärke fest. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Rückgabe:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Liefert oder legt die Audio-Lautstärke fest. Lesen/Schreiben [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Liefert oder legt die genaue Video-Lautstärke als Prozentsatz fest. Der Wert wird als Prozentsatz von 0 bis 100 ausgedrückt. Verwenden Sie diese Eigenschaft, um Lautstärkewerte zu lesen oder zu setzen, die genauer sind als die vordefinierten Stufen, die über die Volume-Eigenschaft verfügbar sind. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lese die aktuelle exakte Lautstärke und setze sie auf 75,5 Prozent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Liefert oder legt die genaue Video-Lautstärke als Prozentsatz fest. Der Wert wird als Prozentsatz von 0 bis 100 ausgedrückt. Verwenden Sie diese Eigenschaft, um Lautstärkewerte zu lesen oder zu setzen, die genauer sind als die vordefinierten Stufen, die über die Volume-Eigenschaft verfügbar sind. Lesen/Schreiben float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lese die aktuelle exakte Lautstärke und setze sie auf 75,5 Prozent.
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
public abstract int getPlayMode()
```

Liefert oder legt den Wiedergabemodus des Videos fest. Lesen/Schreiben [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Rückgabe:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Liefert oder legt den Wiedergabemodus des Videos fest. Lesen/Schreiben [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Liefert oder legt den Namen einer an ein VideoFrame verknüpften Videodatei fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Liefert oder legt den Namen einer an ein VideoFrame verknüpften Videodatei fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Liefert oder legt eingebettetes Videoobjekt fest. Lesen/Schreiben [IVideo](../../com.aspose.slides/ivideo).

**Rückgabe:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Liefert oder legt eingebettetes Videoobjekt fest. Lesen/Schreiben [IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Start zuschneiden [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //setzt die Trimm-Startzeit auf 1 Sekunde
>      videoFrame.setTrimFromStart(1000f);
>      //setzt die Trimm-Endzeit auf 2 Sekunden
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

Start zuschneiden [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //setzt die Trimm-Startzeit auf 1 Sekunde
>      videoFrame.setTrimFromStart(1000f);
>      //setzt die Trimm-Endzeit auf 2 Sekunden
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

Ende zuschneiden [ms]

**Rückgabe:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Ende zuschneiden [ms]

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Liefert die Sammlung geschlossener Untertitel, die dem Audio-Frame zugeordnet sind. Diese Eigenschaft ist nur lesbar und gibt ein [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält.

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
>              // Extrahiert die binären Untertitel-Daten und speichert sie in die Datei
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