---
title: VideoFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getRewindVideo()](#getRewindVideo--) | Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bestimmt, ob ein Video wiederholt wird. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bestimmt, ob ein Video wiederholt wird. |
| [getHideAtShowing()](#getHideAtShowing--) | Bestimmt, ob ein VideoFrame ausgeblendet ist. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bestimmt, ob ein VideoFrame ausgeblendet ist. |
| [getVolume()](#getVolume--) | Gibt die Audio-Lautstärke zurück oder legt sie fest. |
| [setVolume(int value)](#setVolume-int-) | Gibt die Audio-Lautstärke zurück oder legt sie fest. |
| [getPlayMode()](#getPlayMode--) | Gibt den Videowiedergabemodus zurück oder legt ihn fest. |
| [setPlayMode(int value)](#setPlayMode-int-) | Gibt den Videowiedergabemodus zurück oder legt ihn fest. |
| [getFullScreenMode()](#getFullScreenMode--) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt den Namen einer Videodatei zurück oder legt ihn fest, die mit einem VideoFrame verknüpft ist. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt den Namen einer Videodatei zurück oder legt ihn fest, die mit einem VideoFrame verknüpft ist. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Gibt ein eingebettetes Videoobjekt zurück oder legt es fest. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Gibt ein eingebettetes Videoobjekt zurück oder legt es fest. |
| [getTrimFromStart()](#getTrimFromStart--) | Start zuschneiden [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Start zuschneiden [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Ende zuschneiden [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Ende zuschneiden [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Ruft die Sammlung geschlossener Untertitel ab, die dem Video-Frame zugeordnet sind. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Bestimmt, ob ein Video automatisch zum Start zurückgespult wird, sobald der Film zu Ende abgespielt wurde. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Bestimmt, ob ein Video wiederholt wird. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Bestimmt, ob ein Video wiederholt wird. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Bestimmt, ob ein VideoFrame ausgeblendet ist. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Bestimmt, ob ein VideoFrame ausgeblendet ist. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public final int getVolume()
```

Gibt die Audio-Lautstärke zurück oder legt sie fest. Lese/Schreib [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Rückgabe:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Gibt die Audio-Lautstärke zurück oder legt sie fest. Lese/Schreib [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Gibt den Videowiedergabemodus zurück oder legt ihn fest. Lese/Schreib [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Rückgabe:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Gibt den Videowiedergabemodus zurück oder legt ihn fest. Lese/Schreib [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Bestimmt, ob ein Video im Vollbildmodus angezeigt wird. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Gibt den Namen einer Videodatei zurück oder legt ihn fest, die mit einem VideoFrame verknüpft ist. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Gibt den Namen einer Videodatei zurück oder legt ihn fest, die mit einem VideoFrame verknüpft ist. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Gibt ein eingebettetes Videoobjekt zurück oder legt es fest. Lese/Schreib [IVideo](../../com.aspose.slides/ivideo).

**Rückgabe:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Gibt ein eingebettetes Videoobjekt zurück oder legt es fest. Lese/Schreib [IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Start zuschneiden [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //setzt Trim-Startzeit 1 Sekunde
>      videoFrame.setTrimFromStart(1000f);
>      //setzt Trim-Endzeit 2 Sekunden
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Start zuschneiden [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //setzt Trim-Startzeit 1 Sekunde
>      videoFrame.setTrimFromStart(1000f);
>      //setzt Trim-Endzeit 2 Sekunden
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

Ende zuschneiden [ms]

**Rückgabe:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Ende zuschneiden [ms]

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Ruft die Sammlung geschlossener Untertitel ab, die dem Video-Frame zugeordnet sind. Diese Eigenschaft ist nur lesbar und gibt ein [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) zurück, das alle Untertitelspuren enthält.

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