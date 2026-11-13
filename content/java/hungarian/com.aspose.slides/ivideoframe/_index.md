---
title: IVideoFrame
second_title: Aspose.Slides for Java API Referencia
description: Videóklipet jelenít meg egy dián.
type: docs
url: /hu/com.aspose.slides/ivideoframe/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Egy videóklipet jelenít meg egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Meghatározza, hogy a videó automatikusan visszatekerődik-e az elejére, amint a film lejátszása befejeződött. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Meghatározza, hogy a videó automatikusan visszatekerődik-e az elejére, amint a film lejátszása befejeződött. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Meghatározza, hogy a videó ismétlődik-e. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Meghatározza, hogy a videó ismétlődik-e. |
| [getHideAtShowing()](#getHideAtShowing--) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Meghatározza, hogy a VideoFrame rejtett-e. |
| [getVolume()](#getVolume--) | Visszaadja vagy beállítja a hang hangerőt. |
| [setVolume(int value)](#setVolume-int-) | Visszaadja vagy beállítja a hang hangerőt. |
| [getVolumeValue()](#getVolumeValue--) | Visszaadja vagy beállítja a pontos videóhangerőt százalékban. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Visszaadja vagy beállítja a pontos videóhangerőt százalékban. |
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
| [getCaptionTracks()](#getCaptionTracks--) | A hang kerethez kapcsolódó zárt feliratgyűjteményt adja vissza. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Meghatározza, hogy a videó automatikusan visszatekerődik-e az elejére, amint a film lejátszása befejeződött. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Meghatározza, hogy a videó automatikusan visszatekerődik-e az elejére, amint a film lejátszása befejeződött. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Meghatározza, hogy a videó ismétlődik-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Meghatározza, hogy a videó ismétlődik-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Meghatározza, hogy a VideoFrame rejtett-e. Olvasás/írás boolean.

**Visszatérési érték:**
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

Visszaadja vagy beállítja a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Visszatérési érték:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Visszaadja vagy beállítja a hang hangerőt. Olvasás/írás [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Visszaadja vagy beállítja a pontos videóhangerőt százalékban. Az érték 0-tól 100-ig terjedő százalékban van kifejezve. Ezt a tulajdonságot használja a hangerő pontosabb beállításához, mint amilyenek az előre definiált szintek a Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) tulajdonságban érhetők el. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Olvasd ki a jelenlegi pontos hangerőt és állítsd be 75,5 százalékra.
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
public abstract void setVolumeValue(float value)
```

Visszaadja vagy beállítja a pontos videóhangerőt százalékban. Az érték 0-tól 100-ig terjedő százalékban van kifejezve. Ezt a tulajdonságot használja a hangerő pontosabb beállításához, mint amilyenek az előre definiált szintek a Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) tulajdonságban érhetők el. Olvasás/írás float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Olvasd ki a jelenlegi pontos hangerőt és állítsd be 75,5 százalékra.
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
public abstract int getPlayMode()
```

Visszaadja vagy beállítja a videó lejátszási módot. Olvasás/írás [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Visszatérési érték:**
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

**Visszatérési érték:**
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

**Visszatérési érték:**
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

**Visszatérési érték:**
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
>      //állítsd be a kezdő vágási időt 1 másodperc
>      videoFrame.setTrimFromStart(1000f);
>      //állítsd be a vég vágási időt 2 másodperc
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
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
>      //állítsd be a kezdő levágási időt 1 másodperc
>      videoFrame.setTrimFromStart(1000f);
>      //állítsd be a vég levágási időt 2 másodperc
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

**Visszatérési érték:**
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

A hangkerethez kapcsolódó zárt feliratok gyűjteményét adja vissza. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../../com.aspose.slides/icaptionscollection)-t ad vissza, amely az összes felirat sávot tartalmazza.

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
>              // Kinyeri a feliratok bináris adatait és elmenti a fájlba
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