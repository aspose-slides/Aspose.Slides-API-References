---
title: IAudioFrame
second_title: Referência da API Aspose.Slides para Java
description: Representa um clipe de áudio em um slide.
type: docs
url: /pt/com.aspose.slides/iaudioframe/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Representa um clipe de áudio em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Retorna ou define um índice de faixa inicial. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Retorna ou define um índice de faixa inicial. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Retorna ou define um tempo de faixa inicial. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Retorna ou define um tempo de faixa inicial. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Retorna ou define um índice da última faixa. Leitura/gravação int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Retorna ou define um índice da última faixa. Leitura/gravação int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Retorna ou define um tempo da última faixa. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Retorna ou define um tempo da última faixa. |
| [getVolume()](#getVolume--) | Retorna ou define o volume do áudio. |
| [setVolume(int value)](#setVolume-int-) | Retorna ou define o volume do áudio. |
| [getPlayMode()](#getPlayMode--) | Retorna ou define o modo de reprodução do áudio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Retorna ou define o modo de reprodução do áudio. |
| [getHideAtShowing()](#getHideAtShowing--) | Determina se um AudioFrame está oculto. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Determina se um AudioFrame está oculto. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Determina se um áudio está em loop. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Determina se um áudio está em loop. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Determina se um áudio está reproduzindo através dos slides. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Determina se um áudio está reproduzindo através dos slides. |
| [getRewindAudio()](#getRewindAudio--) | Determina se um áudio é rebobinado automaticamente para o início após a reprodução. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Determina se um áudio é rebobinado automaticamente para o início após a reprodução. |
| [getEmbedded()](#getEmbedded--) | Determina se um som está incorporado em uma apresentação. |
| [getLinkPathLong()](#getLinkPathLong--) | Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Retorna ou define objeto de áudio incorporado. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Retorna ou define objeto de áudio incorporado. |
| [getFadeInDuration()](#getFadeInDuration--) | Especifica a duração de tempo para o fade-in inicial da mídia em milissegundos. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Especifica a duração de tempo para o fade-in inicial da mídia em milissegundos. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Especifica a duração de tempo para o fade-out final da mídia em milissegundos. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Especifica a duração de tempo para o fade-out final da mídia em milissegundos. |
| [getVolumeValue()](#getVolumeValue--) | Retorna ou define o volume do áudio em porcentagens. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Retorna ou define o volume do áudio em porcentagens. |
| [getTrimFromStart()](#getTrimFromStart--) | Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Especifica a duração de tempo a ser removida do fim da mídia durante a reprodução, em milissegundos. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Especifica a duração de tempo a ser removida do fim da mídia durante a reprodução, em milissegundos. |
| [getCaptionTracks()](#getCaptionTracks--) | Obtém a coleção de legendas fechadas associadas ao frame de áudio. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Retorna ou define um índice de faixa inicial. Leitura/gravação int.

**Retorna:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Retorna ou define um índice de faixa inicial. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Retorna ou define um tempo de faixa inicial. Leitura/gravação int.

**Retorna:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Retorna ou define um tempo de faixa inicial. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Retorna ou define um índice da última faixa. Leitura/gravação int.

**Retorna:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Retorna ou define um índice da última faixa. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Retorna ou define um tempo da última faixa. Leitura/gravação int.

**Retorna:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Retorna ou define um tempo da última faixa. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Retorna ou define o volume do áudio. Leitura/gravação [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retorna:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Retorna ou define o volume do áudio. Leitura/gravação [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Retorna ou define o modo de reprodução do áudio. Leitura/gravação [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Retorna:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Retorna ou define o modo de reprodução do áudio. Leitura/gravação [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Determina se um AudioFrame está oculto. Leitura/gravação boolean.

**Retorna:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Determina se um AudioFrame está oculto. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Determina se um áudio está em loop. Leitura/gravação boolean.

**Retorna:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Determina se um áudio está em loop. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Determina se um áudio está reproduzindo através dos slides. Leitura/gravação boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Adicionar Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Definir Audio para reproduzir em todos os slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Definir Audio para rebobinar automaticamente ao início após a reprodução
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Retorna:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Determina se um áudio está reproduzindo através dos slides. Leitura/gravação boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Adicionar Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Definir Audio para reproduzir em todos os slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Definir Audio para rebobinar automaticamente ao início após a reprodução
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Determina se um áudio é rebobinado automaticamente para o início após a reprodução. Leitura/gravação boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Adicionar Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Definir Audio para reproduzir em todos os slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Definir Audio para rebobinar automaticamente ao início após a reprodução
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Retorna:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Determina se um áudio é rebobinado automaticamente para o início após a reprodução. Leitura/gravação boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Adicionar Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Definir Audio para reproduzir em todos os slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Definir Audio para rebobinar automaticamente ao início após a reprodução
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Determina se um som está incorporado em uma apresentação. Somente leitura boolean.

**Retorna:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame. Leitura/gravação String.

**Retorna:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Retorna ou define objeto de áudio incorporado. Leitura/gravação [IAudio](../../com.aspose.slides/iaudio).

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Retorna ou define objeto de áudio incorporado. Leitura/gravação [IAudio](../../com.aspose.slides/iaudio).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Especifica a duração de tempo para o fade-in inicial da mídia em milissegundos. Leitura/gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina a duração do fade inicial para 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Especifica a duração de tempo para o fade-in inicial da mídia em milissegundos. Leitura/gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina a duração do fade inicial para 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Especifica a duração de tempo para o fade-out final da mídia em milissegundos. Leitura/gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina a duração do fade final para 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Especifica a duração de tempo para o fade-out final da mídia em milissegundos. Leitura/gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina a duração do fade final para 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Retorna ou define o volume do áudio em porcentagens. Leitura/gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o volume do áudio para 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Retorna ou define o volume do áudio em porcentagens. Leitura/gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o volume do áudio para 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. Leitura/gravação float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o tempo de corte inicial para 1.5 segundos
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. Leitura/gravação float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o tempo de corte inicial para 1.5 segundos
>      audioFrame.setTrimFromStart(1500f);
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
public abstract float getTrimFromEnd()
```

Especifica a duração de tempo a ser removida do fim da mídia durante a reprodução, em milissegundos. Leitura/gravação float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o tempo de corte final para 2 segundos
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Especifica a duração de tempo a ser removida do fim da mídia durante a reprodução, em milissegundos. Leitura/gravação float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o tempo de corte final para 2 segundos
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Obtém a coleção de legendas fechadas associadas ao frame de áudio. Esta propriedade é somente leitura e retorna um [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contendo todas as faixas de legenda.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>     for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>     {
>         if (shape instanceof IAudioFrame)
>         {
>             IAudioFrame audioFrame = (IAudioFrame) shape;
>             // Salve os dados binários da faixa de legenda como um arquivo .vtt
>             for (ICaptions captionTrack : audioFrame.getCaptionTracks())
>             {
>                 FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                 fos.write(captionTrack.getBinaryData());
>                 fos.close();
>             }
>         }
>     }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)