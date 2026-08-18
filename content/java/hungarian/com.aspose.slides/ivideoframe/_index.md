---
title: IVideoFrame
second_title: Aspose.Slides Java API referencia
description: Egy dián lévő videóklipet reprezentál.
type: docs
url: /hu/com.aspose.slides/ivideoframe/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Egy videóklipet reprezentál egy dián.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Meghatározza, hogy a videó automatikusan újraindul-e, amint a lejátszás befejeződik. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Meghatározza, hogy a videó automatikusan újraindul-e, amint a lejátszás befejeződik. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Meghatározza, hogy a videó ismétlésre van-e állítva. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Meghatározza, hogy a videó ismétlésre van-e állítva. |
| [getHideAtShowing()](#getHideAtShowing--) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [getVolume()](#getVolume--) | Visszaadja vagy beállítja a hanghangerőt. |
| [setVolume(int value)](#setVolume-int-) | Visszaadja vagy beállítja a hanghangerőt. |
| [getPlayMode()](#getPlayMode--) | Visszaadja vagy beállítja a videó lejátszási módot. |
| [setPlayMode(int value)](#setPlayMode-int-) | Visszaadja vagy beállítja a videó lejátszási módot. |
| [getFullScreenMode()](#getFullScreenMode--) | Meghatározza, hogy a videó teljes képernyős módban jelenik-e meg. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Meghatározza, hogy a videó teljes képernyős módban jelenik-e meg. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja vagy beállítja egy videófájl nevét, amely a VideoFrame-hez van kapcsolva. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja vagy beállítja egy videófájl nevét, amely a VideoFrame-hez van kapcsolva. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Visszaadja vagy beállítja a beágyazott videóobjektumot. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Visszaadja vagy beállítja a beágyazott videóobjektumot. |
| [getTrimFromStart()](#getTrimFromStart--) | Kezdet levágása [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Kezdet levágása [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Vég levágása [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Vég levágása [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Lekéri a hangkerethez tartozó zárt feliratok gyűjteményét. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Meghatározza, hogy a videó automatikusan újraindul-e, amint a lejátszás befejeződik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Meghatározza, hogy a videó automatikusan újraindul-e, amint a lejátszás befejeződik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Meghatározza, hogy a videó ismétlésre van-e állítva. Olvasás/írás boolean.

**Visszatér:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Meghatározza, hogy a videó ismétlésre van-e állítva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Meghatározza, hogy a VideoFrame rejtett-e. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Meghatározza, hogy a VideoFrame rejtett-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Visszaadja vagy beállítja a hanghangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Visszatér:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Visszaadja vagy beállítja a hanghangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Visszaadja vagy beállítja a videó lejátszási módot. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Visszatér:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Visszaadja vagy beállítja a videó lejátszási módot. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Meghatározza, hogy a videó teljes képernyős módban jelenik-e meg. Olvasás/írás boolean.

**Visszatér:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Meghatározza, hogy a videó teljes képernyős módban jelenik-e meg. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Visszaadja vagy beállítja egy videófájl nevét, amely a VideoFrame-hez van kapcsolva. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Visszaadja vagy beállítja egy videófájl nevét, amely a VideoFrame-hez van kapcsolva. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Visszaadja vagy beállítja a beágyazott videóobjektumot. Olvasás/írás [IVideo](../../com.aspose.slides/ivideo).

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Visszaadja vagy beállítja a beágyazott videóobjektumot. Olvasás/írás [IVideo](../../com.aspose.slides/ivideo).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
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
>      //állítsa be a vágás kezdőidejét 1 másodperc
>      videoFrame.setTrimFromStart(1000f);
>      //állítsa be a vágás befejezőidejét 2 másodperc
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
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
>      //állítsa be a vágás kezdőidejét 1 másodperc
>      videoFrame.setTrimFromStart(1000f);
>      //állítsa be a vágás befejezőidejét 2 másodperc
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
public abstract float getTrimFromEnd()
```

Vég levágása [ms]

**Visszatér:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Vég levágása [ms]

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Lekéri a hangkerethez tartozó zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)-t ad vissza, amely az összes feliratsávot tartalmazza.

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
>              // Kivonja a feliratok bináris adatait és elmenti őket a fájlba
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)