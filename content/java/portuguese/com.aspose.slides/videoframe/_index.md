---
title: VideoFrame
second_title: Referência da API Aspose.Slides para Java
description: Representa um clipe de vídeo em um slide.
type: docs
url: /pt/com.aspose.slides/videoframe/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Representa um clipe de vídeo em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Determina se um vídeo é rebobinado automaticamente para o início assim que o filme termina de ser reproduzido. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Determina se um vídeo é rebobinado automaticamente para o início assim que o filme termina de ser reproduzido. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina se um vídeo está em loop. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina se um vídeo está em loop. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina se um VideoFrame está oculto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina se um VideoFrame está oculto. |
| [getVolume()](#getVolume--) | Retorna ou define o volume de áudio. |
| [setVolume(int value)](#setVolume-int-) | Retorna ou define o volume de áudio. |
| [getVolumeValue()](#getVolumeValue--) | Retorna ou define o volume exato do vídeo como porcentagem. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Retorna ou define o volume exato do vídeo como porcentagem. |
| [getPlayMode()](#getPlayMode--) | Retorna ou define o modo de reprodução do vídeo. |
| [setPlayMode(int value)](#setPlayMode-int-) | Retorna ou define o modo de reprodução do vídeo. |
| [getFullScreenMode()](#getFullScreenMode--) | Determina se um vídeo é exibido em modo tela cheia. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Determina se um vídeo é exibido em modo tela cheia. |
| [getLinkPathLong()](#getLinkPathLong--) | Retorna ou define o nome de um arquivo de vídeo que está vinculado a um VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retorna ou define o nome de um arquivo de vídeo que está vinculado a um VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Retorna ou define objeto de vídeo incorporado. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Retorna ou define objeto de vídeo incorporado. |
| [getTrimFromStart()](#getTrimFromStart--) | Cortar início [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Cortar início [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Cortar fim [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Cortar fim [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Obtém a coleção de legendas fechadas associadas ao video frame. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Determina se um vídeo é rebobinado automaticamente para o início assim que o filme termina de ser reproduzido. Leitura/gravação boolean.

**Retorna:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Determina se um vídeo é rebobinado automaticamente para o início assim que o filme termina de ser reproduzido. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Determina se um vídeo está em loop. Leitura/gravação boolean.

**Retorna:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Determina se um vídeo está em loop. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Determina se um VideoFrame está oculto. Leitura/gravação boolean.

**Retorna:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Determina se um VideoFrame está oculto. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Retorna ou define o volume de áudio. Leitura/gravação [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retorna:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Retorna ou define o volume de áudio. Leitura/gravação [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Retorna ou define o volume exato do vídeo como porcentagem. O valor é expresso como uma porcentagem de 0 a 100. Use esta propriedade para ler ou definir valores de volume mais precisos do que os níveis predefinidos disponíveis através da propriedade \#getVolume.getVolume/\#setVolume(int).setVolume(int). Leitura/gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Leia o volume exato atual e defina-o para 75,5 por cento.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Retorna ou define o volume exato do vídeo como porcentagem. O valor é expresso como uma porcentagem de 0 a 100. Use esta propriedade para ler ou definir valores de volume mais precisos do que os níveis predefinidos disponíveis através da propriedade \#getVolume.getVolume/\#setVolume(int).setVolume(int). Leitura/gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Leia o volume exato atual e defina-o para 75,5 por cento.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Retorna ou define o modo de reprodução do vídeo. Leitura/gravação [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Retorna:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Retorna ou define o modo de reprodução do vídeo. Leitura/gravação [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Determina se um vídeo é exibido em modo tela cheia. Leitura/gravação boolean.

**Retorna:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Determina se um vídeo é exibido em modo tela cheia. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Retorna ou define o nome de um arquivo de vídeo que está vinculado a um VideoFrame. Leitura/gravação String.

**Retorna:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Retorna ou define o nome de um arquivo de vídeo que está vinculado a um VideoFrame. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Retorna ou define objeto de vídeo incorporado. Leitura/gravação [IVideo](../../com.aspose.slides/ivideo).

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Retorna ou define objeto de vídeo incorporado. Leitura/gravação [IVideo](../../com.aspose.slides/ivideo).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Cortar início [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //defina o início do recorte 1s
>      videoFrame.setTrimFromStart(1000f);
>      //defina o fim do recorte 2s
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Cortar início [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //defina o início do recorte 1s
>      videoFrame.setTrimFromStart(1000f);
>      //defina o fim do recorte 2s
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Cortar fim [ms]

**Retorna:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Cortar fim [ms]

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Obtém a coleção de legendas fechadas associadas ao video frame. Esta propriedade é somente leitura e retorna um [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contendo todas as faixas de legendas.

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

**Retorna:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)