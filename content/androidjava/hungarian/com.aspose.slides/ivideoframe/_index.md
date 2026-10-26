---
title: IVideoFrame
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy videoklipet ábrázol egy dián.
type: docs
url: /hu/com.aspose.slides/ivideoframe/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Egy videoklipet ábrázol egy dián.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Meghatározza, hogy egy videó automatikusan visszatekerődik-e a kezdetre, amint a lejátszás befejeződött. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Meghatározza, hogy egy videó automatikusan visszatekerődik-e a kezdetre, amint a lejátszás befejeződött. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Meghatározza, hogy egy videó ismétlődő-e. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Meghatározza, hogy egy videó ismétlődő-e. |
| [getHideAtShowing()](#getHideAtShowing--) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [getVolume()](#getVolume--) | Visszaadja vagy beállítja a hangszintet. |
| [setVolume(int value)](#setVolume-int-) | Visszaadja vagy beállítja a hangszintet. |
| [getPlayMode()](#getPlayMode--) | Visszaadja vagy beállítja a videó lejátszási módját. |
| [setPlayMode(int value)](#setPlayMode-int-) | Visszaadja vagy beállítja a videó lejátszási módját. |
| [getFullScreenMode()](#getFullScreenMode--) | Meghatározza, hogy a videó teljes képernyős módban jelenik-e meg. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Meghatározza, hogy a videó teljes képernyős módban jelenik-e meg. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja vagy beállítja egy videófájl nevét, amely a VideoFrame-hez van kapcsolva. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja vagy beállítja egy videófájl nevét, amely a VideoFrame-hez van kapcsolva. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Visszaadja vagy beállítja a beágyazott videóobjektumot. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Visszaadja vagy beállítja a beágyazott videóobjektumot. |
| [getTrimFromStart()](#getTrimFromStart--) | Kezdet vágása [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Kezdet vágása [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Vég vágása [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Vég vágása [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Lekéri a hangkerethez társított zárt feliratok gyűjteményét. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Meghatározza, hogy egy videó automatikusan visszatekerődik-e a kezdetre, amint a lejátszás befejeződött. Olvasás/írás boolean.

**Visszatér:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Meghatározza, hogy egy videó automatikusan visszatekerődik-e a kezdetre, amint a lejátszás befejeződött. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Meghatározza, hogy egy videó ismétlődő-e. Olvasás/írás boolean.

**Visszatér:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Meghatározza, hogy egy videó ismétlődő-e. Olvasás/írás boolean.

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

Visszaadja vagy beállítja a hangszintet. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Visszatér:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Visszaadja vagy beállítja a hangszintet. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Visszaadja vagy beállítja a videó lejátszási módját. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Visszatér:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Visszaadja vagy beállítja a videó lejátszási módját. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

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

Kezdet vágása [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //set triming start time 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //set triming end time 2sec
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

Kezdet vágása [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //set triming start time 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //set triming end time 2sec
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

Vég vágása [ms]

**Visszatér:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Vég vágása [ms]

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Lekéri a hangkerethez társított zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és visszaad egy [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)-t, amely az összes felirat sávot tartalmazza.

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
>              // Kivonja a feliratok bináris adatait, és elmenti őket a fájlba
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