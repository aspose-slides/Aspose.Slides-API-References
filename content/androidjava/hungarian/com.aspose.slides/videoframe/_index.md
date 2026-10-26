---
title: VideoFrame
second_title: Aspose.Slides Androidra a Java API referencián keresztül
description: Egy dián lévő videóklipet ábrázol.
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

Egy videóklipet ábrázol egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Meghatározza, hogy a videó automatikusan visszatekerődik-e a kezdetre, amint a film lejátszása befejeződött. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Meghatározza, hogy a videó automatikusan visszatekerődik-e a kezdetre, amint a film lejátszása befejeződött. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Meghatározza, hogy a videó ismétlődik-e. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Meghatározza, hogy a videó ismétlődik-e. |
| [getHideAtShowing()](#getHideAtShowing--) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [getVolume()](#getVolume--) | Visszaadja vagy beállítja a hangerejét. |
| [setVolume(int value)](#setVolume-int-) | Visszaadja vagy beállítja a hangerejét. |
| [getPlayMode()](#getPlayMode--) | Visszaadja vagy beállítja a videó lejátszási módját. |
| [setPlayMode(int value)](#setPlayMode-int-) | Visszaadja vagy beállítja a videó lejátszási módját. |
| [getFullScreenMode()](#getFullScreenMode--) | Meghatározza, hogy a videó teljes képernyő módban jelenik-e meg. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Meghatározza, hogy a videó teljes képernyő módban jelenik-e meg. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja vagy beállítja egy video fájl nevét, amely a VideoFrame-hez kapcsolódik. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja vagy beállítja egy video fájl nevét, amely a VideoFrame-hez kapcsolódik. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Visszaadja vagy beállítja a beágyazott video objektumot. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Visszaadja vagy beállítja a beágyazott video objektumot. |
| [getTrimFromStart()](#getTrimFromStart--) | Kezdés levágása [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Kezdés levágása [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Vég levágása [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Vég levágása [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Megkapja a video kerethez kapcsolódó lezárt feliratok gyűjteményét. |

### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Meghatározza, hogy a videó automatikusan visszatekerődik-e a kezdetre, amint a film lejátszása befejeződik. Olvasás/írás boolean.

**Visszatér:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Meghatározza, hogy a videó automatikusan visszatekerődik-e a kezdetre, amint a film lejátszása befejeződik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Meghatározza, hogy a videó ismétlődik-e. Olvasás/írás boolean.

**Visszatér:**
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

**Visszatér:**
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

Visszaadja vagy beállítja a hangerejét. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Visszatér:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Visszaadja vagy beállítja a hangerejét. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Visszaadja vagy beállítja a videó lejátszási módját. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Visszatér:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Visszaadja vagy beállítja a videó lejátszási módját. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Meghatározza, hogy a videó teljes képernyő módban jelenik-e meg. Olvasás/írás boolean.

**Visszatér:**
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

Visszaadja vagy beállítja egy video fájl nevét, amely a VideoFrame-hez kapcsolódik. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Visszaadja vagy beállítja egy video fájl nevét, amely a VideoFrame-hez kapcsolódik. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Visszaadja vagy beállítja a beágyazott video objektumot. Olvasás/írás [IVideo](../../com.aspose.slides/ivideo).

**Visszatér:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Visszaadja vagy beállítja a beágyazott video objektumot. Olvasás/írás [IVideo](../../com.aspose.slides/ivideo).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Kezdés levágása [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //állítsa be a vágás kezdőidőpontját 1 másodperc
>      videoFrame.setTrimFromStart(1000f);
>      //állítsa be a vágás befejező időpontját 2 másodperc
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Kezdés levágása [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //állítsa be a vágás kezdő időpontját 1 másodperc
>      videoFrame.setTrimFromStart(1000f);
>      //állítsa be a vágás befejező időpontját 2 másodperc
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

Vég levágása [ms]

**Visszatér:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Vég levágása [ms]

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Megkapja a video kerethez kapcsolódó lezárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)-t ad vissza, amely az összes felirat sávot tartalmazza.

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
>              // Kinyeri a feliratok bináris adatait és elmenti a fájlt
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