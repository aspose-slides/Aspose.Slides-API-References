---
title: VideoFrame
second_title: Aspose.Slides a Java API Referenciája
description: Egy dián lévő videoklipet képvisel.
type: docs
url: /hu/com.aspose.slides/videoframe/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Minden megvalósított interfész:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Egy videoklipet képvisel egy dián.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Megállapítja, hogy a videó automatikusan visszatekerődik-e a kezdetre, amint a film lejátszása befejeződött. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Megállapítja, hogy a videó automatikusan visszatekerődik-e a kezdetre, amint a film lejátszása befejeződött. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Megállapítja, hogy a videó ismétlődik-e. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Megállapítja, hogy a videó ismétlődik-e. |
| [getHideAtShowing()](#getHideAtShowing--) | Megállapítja, hogy a VideoFrame rejtett-e. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Megállapítja, hogy a VideoFrame rejtett-e. |
| [getVolume()](#getVolume--) | Visszaadja vagy beállítja a hang hangerőt. |
| [setVolume(int value)](#setVolume-int-) | Visszaadja vagy beállítja a hang hangerőt. |
| [getPlayMode()](#getPlayMode--) | Visszaadja vagy beállítja a videó lejátszási módot. |
| [setPlayMode(int value)](#setPlayMode-int-) | Visszaadja vagy beállítja a videó lejátszási módot. |
| [getFullScreenMode()](#getFullScreenMode--) | Megállapítja, hogy a videó teljes képernyős módban jelenik-e meg. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Megállapítja, hogy a videó teljes képernyős módban jelenik-e meg. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja vagy beállítja egy videofájl nevét, amely a VideoFrame-hez kapcsolódik. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja vagy beállítja egy videofájl nevét, amely a VideoFrame-hez kapcsolódik. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Visszaadja vagy beállítja a beágyazott videóobjektumot. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Visszaadja vagy beállítja a beágyazott videóobjektumot. |
| [getTrimFromStart()](#getTrimFromStart--) | Kezdet levágása [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Kezdet levágása [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Vágás vége [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Vágás vége [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Lekéri a videókerethez kapcsolódó zárt feliratok gyűjteményét. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Megállapítja, hogy a videó automatikusan visszatekerődik-e a kezdetre, amint a film lejátszása befejeződött. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Megállapítja, hogy a videó automatikusan visszatekerődik-e a kezdetre, amint a film lejátszása befejeződött. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Megállapítja, hogy a videó ismétlődik-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Megállapítja, hogy a videó ismétlődik-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Megállapítja, hogy a VideoFrame rejtett-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Megállapítja, hogy a VideoFrame rejtett-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Visszaadja vagy beállítja a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Visszatérési érték:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Visszaadja vagy beállítja a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Visszaadja vagy beállítja a videó lejátszási módot. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Visszatérési érték:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Visszaadja vagy beállítja a videó lejátszási módot. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Megállapítja, hogy a videó teljes képernyős módban jelenik-e meg. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Megállapítja, hogy a videó teljes képernyős módban jelenik-e meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Visszaadja vagy beállítja egy videofájl nevét, amely a VideoFrame-hez kapcsolódik. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Visszaadja vagy beállítja egy videofájl nevét, amely a VideoFrame-hez kapcsolódik. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Visszaadja vagy beállítja a beágyazott videóobjektumot. Olvasás/írás [IVideo](../../com.aspose.slides/ivideo).

**Visszatérési érték:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Visszaadja vagy beállítja a beágyazott videóobjektumot. Olvasás/írás [IVideo](../../com.aspose.slides/ivideo).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Kezdet levágása [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //állítsa be a vágás kezdő időt 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //állítsa be a vágás befejező időt 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Kezdet levágása [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //állítsa be a vágás kezdő időt 1 sec
>      videoFrame.setTrimFromStart(1000f);
>      //állítsa be a vágás befejező időt 2 sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Vágás vége [ms]

**Visszatérési érték:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Vágás vége [ms]

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Lekéri a videókerethez kapcsolódó zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)-t ad vissza, amely az összes feliratsávot tartalmazza.

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
>              // Kinyeri a feliratok bináris adatát és elmenti a fájlba
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)