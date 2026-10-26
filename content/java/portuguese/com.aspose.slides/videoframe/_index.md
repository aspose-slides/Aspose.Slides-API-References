---
title: VideoFrame
second_title: Referência da API Aspose.Slides para Java
description: Representa um clipe de vídeo em um slide.
type: docs
url: /pt/com.aspose.slides/videoframe/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Todas as interfaces implementadas:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Representa um clipe de vídeo em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Determina se um vídeo é reiniciado automaticamente para o início assim que o filme termina de ser reproduzido. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Determina se um vídeo é reiniciado automaticamente para o início assim que o filme termina de ser reproduzido. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina se um vídeo é reproduzido em loop. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina se um vídeo é reproduzido em loop. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina se um VideoFrame está oculto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina se um VideoFrame está oculto. |
| [getVolume()](#getVolume--) | Retorna ou define o volume de áudio. |
| [setVolume(int value)](#setVolume-int-) | Retorna ou define o volume de áudio. |
| [getPlayMode()](#getPlayMode--) | Retorna ou define o modo de reprodução de vídeo. |
| [setPlayMode(int value)](#setPlayMode-int-) | Retorna ou define o modo de reprodução de vídeo. |
| [getFullScreenMode()](#getFullScreenMode--) | Determina se um vídeo é exibido em modo de tela cheia. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Determina se um vídeo é exibido em modo de tela cheia. |
| [getLinkPathLong()](#getLinkPathLong--) | Retorna ou define o nome de um arquivo de vídeo que está vinculado a um VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retorna ou define o nome de um arquivo de vídeo que está vinculado a um VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Retorna ou define o objeto de vídeo incorporado. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Retorna ou define o objeto de vídeo incorporado. |
| [getTrimFromStart()](#getTrimFromStart--) | Corte inicial [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Corte inicial [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Corte final [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Corte final [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Obtém a coleção de legendas fechadas associadas ao quadro de vídeo. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```


Determina se um vídeo é reiniciado automaticamente para o início assim que o filme termina de ser reproduzido. Leitura/gravação boolean.

**Returns:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```


Determina se um vídeo é reiniciado automaticamente para o início assim que o filme termina de ser reproduzido. Leitura/gravação boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```


Determina se um vídeo é reproduzido em loop. Leitura/gravação boolean.

**Returns:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```


Determina se um vídeo é reproduzido em loop. Leitura/gravação boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```


Determina se um VideoFrame está oculto. Leitura/gravação boolean.

**Returns:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```


Determina se um VideoFrame está oculto. Leitura/gravação boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```


Retorna ou define o volume de áudio. Leitura/gravação [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returns:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```


Retorna ou define o volume de áudio. Leitura/gravação [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```


Retorna ou define o modo de reprodução de vídeo. Leitura/gravação [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Returns:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```


Retorna ou define o modo de reprodução de vídeo. Leitura/gravação [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```


Determina se um vídeo é exibido em modo de tela cheia. Leitura/gravação boolean.

**Returns:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```


Determina se um vídeo é exibido em modo de tela cheia. Leitura/gravação boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Retorna ou define o nome de um arquivo de vídeo que está vinculado a um VideoFrame. Leitura/gravação String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Retorna ou define o nome de um arquivo de vídeo que está vinculado a um VideoFrame. Leitura/gravação String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```


Retorna ou define o objeto de vídeo incorporado. Leitura/gravação [IVideo](../../com.aspose.slides/ivideo).

**Returns:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```


Retorna ou define o objeto de vídeo incorporado. Leitura/gravação [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```


Corte inicial [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //definir tempo de início do corte 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //definir tempo de fim do corte 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```


Corte inicial [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //definir tempo de início do corte 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //definir tempo de fim do corte 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```


Corte final [ms]

**Returns:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```


Corte final [ms]

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```


Obtém a coleção de legendas fechadas associadas ao quadro de vídeo. Esta propriedade é somente leitura e retorna um [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contendo todas as faixas de legenda.

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
>              // Extrai os dados binários das legendas e os salva no arquivo
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)