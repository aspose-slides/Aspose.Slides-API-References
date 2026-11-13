---
title: VideoFrame
second_title: Aspose.Slides voor Java API Referentie
description: Representeert een video-clip op een dia.
type: docs
url: /nl/com.aspose.slides/videoframe/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Representeert een video-clip op een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bepaalt of een video in een lus wordt afgespeeld. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bepaalt of een video in een lus wordt afgespeeld. |
| [getHideAtShowing()](#getHideAtShowing--) | Bepaalt of een VideoFrame verborgen is. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bepaalt of een VideoFrame verborgen is. |
| [getVolume()](#getVolume--) | Geeft of stelt het audiovolume in. |
| [setVolume(int value)](#setVolume-int-) | Geeft of stelt het audiovolume in. |
| [getVolumeValue()](#getVolumeValue--) | Geeft of stelt het exacte video-volume als een percentage in. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Geeft of stelt het exacte video-volume als een percentage in. |
| [getPlayMode()](#getPlayMode--) | Geeft of stelt de afspeelmodus van de video in. |
| [setPlayMode(int value)](#setPlayMode-int-) | Geeft of stelt de afspeelmodus van de video in. |
| [getFullScreenMode()](#getFullScreenMode--) | Bepaalt of een video wordt weergegeven in volledig-schermmodus. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bepaalt of een video wordt weergegeven in volledig-schermmodus. |
| [getLinkPathLong()](#getLinkPathLong--) | Geeft of stelt de naam van een videobestand in dat is gekoppeld aan een VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Geeft of stelt de naam van een videobestand in dat is gekoppeld aan een VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Geeft of stelt een ingebed video-object in. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Geeft of stelt een ingebed video-object in. |
| [getTrimFromStart()](#getTrimFromStart--) | Begin trimmen [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Begin trimmen [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Eind trimmen [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Eind trimmen [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Haalt de collectie van gesloten bijschriften op die aan het video-frame zijn gekoppeld. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```


Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. Lezen/Schrijven boolean.

**Retour:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```


Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


Bepaalt of een video in een lus wordt afgespeeld. Lezen/Schrijven boolean.

**Retour:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


Bepaalt of een video in een lus wordt afgespeeld. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


Bepaalt of een VideoFrame verborgen is. Lezen/Schrijven boolean.

**Retour:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


Bepaalt of een VideoFrame verborgen is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```


Geeft of stelt het audiovolume in. Lezen/Schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retour:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```


Geeft of stelt het audiovolume in. Lezen/Schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```


Geeft of stelt het exacte video-volume als een percentage in. De waarde wordt uitgedrukt als een percentage van 0 tot 100. Gebruik deze eigenschap om volume-waarden te lezen of in te stellen die nauwkeuriger zijn dan de vooraf gedefinieerde niveaus die beschikbaar zijn via de \#getVolume.getVolume/\#setVolume(int).setVolume(int) eigenschap. Lezen/Schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Read the current exact volume and set it to 75.5 percent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```


Geeft of stelt het exacte video-volume als een percentage in. De waarde wordt uitgedrukt als een percentage van 0 tot 100. Gebruik deze eigenschap om volume-waarden te lezen of in te stellen die nauwkeuriger zijn dan de vooraf gedefinieerde niveaus die beschikbaar zijn via de \#getVolume.getVolume/\#setVolume(int).setVolume(int) eigenschap. Lezen/Schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Read the current exact volume and set it to 75.5 percent.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```


Geeft of stelt de afspeelmodus van de video in. Lezen/Schrijven [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Retour:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```


Geeft of stelt de afspeelmodus van de video in. Lezen/Schrijven [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```


Bepaalt of een video wordt weergegeven in volledig-schermmodus. Lezen/Schrijven boolean.

**Retour:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```


Bepaalt of een video wordt weergegeven in volledig-schermmodus. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Geeft of stelt de naam van een videobestand in dat is gekoppeld aan een VideoFrame. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Geeft of stelt de naam van een videobestand in dat is gekoppeld aan een VideoFrame. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```


Geeft of stelt een ingebed video-object in. Lezen/Schrijven [IVideo](../../com.aspose.slides/ivideo).

**Retour:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```


Geeft of stelt een ingebed video-object in. Lezen/Schrijven [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```


Begin trimmen [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //set triming start time 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //set triming end time 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```


Begin trimmen [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //stel trim starttijd in 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //stel trim eindtijd in 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```


Eind trimmen [ms]

**Retour:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```


Eind trimmen [ms]

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```


Haalt de collectie van gesloten bijschriften op die aan het video-frame zijn gekoppeld. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) met alle ondertitel-tracks.

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
>              // Extraheert de binaire bijschriftgegevens en slaat ze op in het bestand
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)