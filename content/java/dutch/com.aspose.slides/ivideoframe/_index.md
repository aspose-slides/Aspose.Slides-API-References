---
title: IVideoFrame
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een video-fragment voor op een dia.
type: docs
url: /nl/com.aspose.slides/ivideoframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Stelt een videofragment voor op een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Bepaalt of een video in een lus wordt afgespeeld. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Bepaalt of een video in een lus wordt afgespeeld. |
| [getHideAtShowing()](#getHideAtShowing--) | Bepaalt of een VideoFrame verborgen is. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Bepaalt of een VideoFrame verborgen is. |
| [getVolume()](#getVolume--) | Geeft de audiovolume terug of stelt deze in. |
| [setVolume(int value)](#setVolume-int-) | Geeft de audiovolume terug of stelt deze in. |
| [getVolumeValue()](#getVolumeValue--) | Geeft het exacte video-volume als een percentage terug of stelt dit in. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Geeft het exacte video-volume als een percentage terug of stelt dit in. |
| [getPlayMode()](#getPlayMode--) | Geeft de afspeelmodus van de video terug of stelt deze in. |
| [setPlayMode(int value)](#setPlayMode-int-) | Geeft de afspeelmodus van de video terug of stelt deze in. |
| [getFullScreenMode()](#getFullScreenMode--) | Bepaalt of een video wordt weergegeven in volledig scherm. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Bepaalt of een video wordt weergegeven in volledig scherm. |
| [getLinkPathLong()](#getLinkPathLong--) | Geeft de naam van een videobestand dat aan een VideoFrame is gekoppeld terug of stelt deze in. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Geeft de naam van een videobestand dat aan een VideoFrame is gekoppeld terug of stelt deze in. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Geeft een ingebed video-object terug of stelt dit in. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Geeft een ingebed video-object terug of stelt dit in. |
| [getTrimFromStart()](#getTrimFromStart--) | Begintrim [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Begintrim [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Eindtrim [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Eindtrim [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Haalt de collectie van gesloten ondertitels op die bij het audio-frame horen. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. Lezen/schrijven boolean.

**Retour:**  
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Bepaalt of een video automatisch wordt teruggespoeld naar het begin zodra de film is afgelopen. Lezen/schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Bepaalt of een video in een lus wordt afgespeeld. Lezen/schrijven boolean.

**Retour:**  
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Bepaalt of een video in een lus wordt afgespeeld. Lezen/schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Bepaalt of een VideoFrame verborgen is. Lezen/schrijven boolean.

**Retour:**  
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Bepaalt of een VideoFrame verborgen is. Lezen/schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Geeft de audiovolume terug of stelt deze in. Lezen/schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retour:**  
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Geeft de audiovolume terug of stelt deze in. Lezen/schrijven [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Geeft het exacte video-volume als een percentage terug of stelt dit in. De waarde wordt uitgedrukt als een percentage van 0 tot 100. Gebruik deze eigenschap om volume-waarden te lezen of in te stellen die nauwkeuriger zijn dan de vooraf gedefinieerde niveaus die beschikbaar zijn via de Volume-eigenschap. Lezen/schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lees het huidige exacte volume en stel het in op 75,5 procent.
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
public abstract void setVolumeValue(float value)
```

Geeft het exacte video-volume als een percentage terug of stelt dit in. De waarde wordt uitgedrukt als een percentage van 0 tot 100. Gebruik deze eigenschap om volume-waarden te lezen of in te stellen die nauwkeuriger zijn dan de vooraf gedefinieerde niveaus die beschikbaar zijn via de Volume-eigenschap. Lezen/schrijven float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lees het huidige exacte volume en stel het in op 75,5 procent.
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
public abstract int getPlayMode()
```

Geeft de afspeelmodus van de video terug of stelt deze in. Lezen/schrijven [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Retour:**  
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Geeft de afspeelmodus van de video terug of stelt deze in. Lezen/schrijven [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Bepaalt of een video wordt weergegeven in volledig scherm. Lezen/schrijven boolean.

**Retour:**  
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Bepaalt of een video wordt weergegeven in volledig scherm. Lezen/schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Geeft de naam van een videobestand dat aan een VideoFrame is gekoppeld terug of stelt deze in. Lezen/schrijven String.

**Retour:**  
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Geeft de naam van een videobestand dat aan een VideoFrame is gekoppeld terug of stelt deze in. Lezen/schrijven String.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Geeft een ingebed video-object terug of stelt dit in. Lezen/schrijven [IVideo](../../com.aspose.slides/ivideo).

**Retour:**  
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Geeft een ingebed video-object terug of stelt dit in. Lezen/schrijven [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Begintrim [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //stel trim starttijd in op 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //stel trim eindtijd in op 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**  
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Begintrim [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //stel trim starttijd in op 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //stel trim eindtijd in op 2sec
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
public abstract float getTrimFromEnd()
```

Eindtrim [ms]

**Retour:**  
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Eindtrim [ms]

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Haalt de collectie van gesloten ondertitels op die bij het audio-frame horen. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) met alle ondertitel-tracks.

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
>              // Haalt de binaire gegevens van de ondertitels op en slaat ze op in het bestand
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