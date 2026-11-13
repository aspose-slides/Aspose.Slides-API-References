---
title: VideoFrame
second_title: Aspose.Slides Java API hivatkozás
description: Videoklipet ábrázol egy dián.
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

Egy videoklipet ábrázol egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Meghatározza, hogy a videó automatikusan újraindul-e a film lejátszása befejeződöttével. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Meghatározza, hogy a videó automatikusan újraindul-e a film lejátszása befejeződöttével. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Meghatározza, hogy a videó ismétlődik-e. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Meghatározza, hogy a videó ismétlődik-e. |
| [getHideAtShowing()](#getHideAtShowing--) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [getVolume()](#getVolume--) | Visszatér vagy beállítja a hang hangerőt. |
| [setVolume(int value)](#setVolume-int-) | Visszatér vagy beállítja a hang hangerőt. |
| [getVolumeValue()](#getVolumeValue--) | Visszatér vagy beállítja a pontos videó hangerőt százalékban. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Visszatér vagy beállítja a pontos videó hangerőt százalékban. |
| [getPlayMode()](#getPlayMode--) | Visszatér vagy beállítja a videó lejátszási módot. |
| [setPlayMode(int value)](#setPlayMode-int-) | Visszatér vagy beállítja a videó lejátszási módot. |
| [getFullScreenMode()](#getFullScreenMode--) | Meghatározza, hogy a videó teljes képernyő módban jelenik-e meg. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Meghatározza, hogy a videó teljes képernyő módban jelenik-e meg. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszatér vagy beállítja egy videofájl nevét, amely a VideoFrame-hez van kapcsolva. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszatér vagy beállítja egy videofájl nevét, amely a VideoFrame-hez van kapcsolva. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Visszatér vagy beállítja a beágyazott videó objektumot. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Visszatér vagy beállítja a beágyazott videó objektumot. |
| [getTrimFromStart()](#getTrimFromStart--) | Kezdő vágás [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Kezdő vágás [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Vágás vége [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Vágás vége [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Visszaadja a videókerethez kapcsolt zárt feliratok gyűjteményét. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Meghatározza, hogy a videó automatikusan újraindul-e a film lejátszása befejeződöttével. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Meghatározza, hogy a videó automatikusan újraindul-e a film lejátszása befejeződöttével. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Meghatározza, hogy a videó ismétlődik-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Meghatározza, hogy a videó ismétlődik-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Meghatározza, hogy a VideoFrame rejtett-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Meghatározza, hogy a VideoFrame rejtett-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Visszatér vagy beállítja a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Visszatérési érték:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Visszatér vagy beállítja a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Visszatér vagy beállítja a pontos videó hangerőt százalékban. Az érték 0-tól 100-ig terjedő százalékban van megadva. Ezt a tulajdonságot használja a hangerő értékek olvasásához vagy beállításához, ha pontosabbak kell legyenek, mint a \#getVolume.getVolume/\#setVolume(int) tulajdonság által biztosított előre definiált szintek. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Olvassa be a jelenlegi pontos hangerőt és állítsa be 75.5 százalékra.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Visszatér vagy beállítja a pontos videó hangerőt százalékban. Az érték 0-tól 100-ig terjedő százalékban van megadva. Ezt a tulajdonságot használja a hangerő értékek olvasásához vagy beállításához, ha pontosabbak kell legyenek, mint a \#getVolume.getVolume/\#setVolume(int) tulajdonság által biztosított előre definiált szintek. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Olvassa be a jelenlegi pontos hangerőt és állítsa be 75.5 százalékra.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Visszatér vagy beállítja a videó lejátszási módot. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Visszatérési érték:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Visszatér vagy beállítja a videó lejátszási módot. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Meghatározza, hogy a videó teljes képernyő módban jelenik-e meg. Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Meghatározza, hogy a videó teljes képernyő módban jelenik-e meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Visszatér vagy beállítja egy videofájl nevét, amely a VideoFrame-hez van kapcsolva. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Visszatér vagy beállítja egy videofájl nevét, amely a VideoFrame-hez van kapcsolva. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Visszatér vagy beállítja a beágyazott videó objektumot. Olvasás/írás [IVideo](../../com.aspose.slides/ivideo).

**Visszatérési érték:**
[IVideo](../../com.aspose.slides/ivideo)

### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Visszatér vagy beállítja a beágyazott videó objektumot. Olvasás/írás [IVideo](../../com.aspose.slides/ivideo).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Kezdő vágás [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //állítsa be a vágás kezdési időpontját 1 másodperc
>      videoFrame.setTrimFromStart(1000f);
>      //állítsa be a vágás befejezési időpontját 2 másodperc
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

Kezdő vágás [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //állítsa be a vágás kezdési időpontját 1 másodperc
>      videoFrame.setTrimFromStart(1000f);
>      //állítsa be a vágás befejezési időpontját 2 másodperc
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

Visszaadja a videókerethez kapcsolt zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasásra szolgál, és egy [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) objektumot ad vissza, amely az összes feliratsávot tartalmazza.

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
>              // Kinyeri a feliratok bináris adatait, és a fájlba menti.
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