---
title: AudioFrame
second_title: Referência da API Java para Aspose.Slides para Android
description: Representa um clipe de áudio em um slide.
type: docs
url: /pt/com.aspose.slides/audioframe/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Representa um clipe de áudio em um slide.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Obtém a forma AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Define o modo de reprodução para reproduzir ao clicar
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Define o volume como Baixo
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Define o áudio para reproduzir em todos os slides
>      audioFrame.setPlayAcrossSlides(true);
>      // Desativa o loop para o áudio
>      audioFrame.setPlayLoopMode(false);
>      // Oculta o AudioFrame durante a apresentação
>      audioFrame.setHideAtShowing(true);
>      // Rebobina o áudio para o início após a reprodução
>      audioFrame.setRewindAudio(true);
>      // Salva o arquivo PowerPoint no disco
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descrição |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Retorna ou define um índice de faixa inicial. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Retorna ou define um índice de faixa inicial. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Retorna ou define um tempo de faixa inicial. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Retorna ou define um tempo de faixa inicial. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Retorna ou define um índice da última faixa Leitura/Gravação  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Retorna ou define um índice da última faixa Leitura/Gravação  int . |
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
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Determina se o áudio está sendo reproduzido em todos os slides. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Determina se o áudio está sendo reproduzido em todos os slides. |
| [getRewindAudio()](#getRewindAudio--) | Determina se o áudio é rebobinado automaticamente para o início após a reprodução. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Determina se o áudio é rebobinado automaticamente para o início após a reprodução. |
| [getEmbedded()](#getEmbedded--) | Determina se um som está incorporado a uma apresentação. |
| [getLinkPathLong()](#getLinkPathLong--) | Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Retorna ou define o objeto de áudio incorporado. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Retorna ou define o objeto de áudio incorporado. |
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
| [getCaptionTracks()](#getCaptionTracks--) | Obtém a coleção de legendas fechadas associadas ao quadro de áudio. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Retorna ou define um índice de faixa inicial. Leitura/Gravação  int .

**Retorna:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Retorna ou define um índice de faixa inicial. Leitura/Gravação  int .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Retorna ou define um tempo de faixa inicial. Leitura/Gravação  int .

**Retorna:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Retorna ou define um tempo de faixa inicial. Leitura/Gravação  int .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Retorna ou define um índice da última faixa Leitura/Gravação  int .

**Retorna:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Retorna ou define um índice da última faixa Leitura/Gravação  int .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Retorna ou define um tempo da última faixa. Leitura/Gravação  int .

**Retorna:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Retorna ou define um tempo da última faixa. Leitura/Gravação  int .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Retorna ou define o volume do áudio. Leitura/Gravação [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retorna:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Retorna ou define o volume do áudio. Leitura/Gravação [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Retorna ou define o modo de reprodução do áudio. Leitura/Gravação [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Retorna:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Retorna ou define o modo de reprodução do áudio. Leitura/Gravação [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Determina se um AudioFrame está oculto. Leitura/Gravação  boolean .

**Retorna:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Determina se um AudioFrame está oculto. Leitura/Gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Determina se um áudio está em loop. Leitura/Gravação  boolean .

**Retorna:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Determina se um áudio está em loop. Leitura/Gravação  boolean .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Determina se o áudio está sendo reproduzido em todos os slides. Leitura/Gravação  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Adiciona quadro de áudio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Define o áudio para reproduzir em todos os slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Define o áudio para rebobinar automaticamente ao início após a reprodução
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
public final void setPlayAcrossSlides(boolean value)
```

Determina se o áudio está sendo reproduzido em todos os slides. Leitura/Gravação  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Adicionar quadro de áudio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Definir áudio para reproduzir em todos os slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Definir áudio para rebobinar automaticamente ao início após a reprodução
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
public final boolean getRewindAudio()
```

Determina se o áudio é rebobinado automaticamente para o início após a reprodução. Leitura/Gravação  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Add Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Set Audio to play across the slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Set Audio to automatically rewind to start after playing
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
public final void setRewindAudio(boolean value)
```

Determina se o áudio é rebobinado automaticamente para o início após a reprodução. Leitura/Gravação  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Adicionar quadro de áudio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Definir áudio para reproduzir em todos os slides
>       audioFrame.setPlayAcrossSlides(true);
>       // Definir áudio para rebobinar automaticamente ao início após a reprodução
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
public final boolean getEmbedded()
```

Determina se um som está incorporado a uma apresentação. Somente leitura  boolean .

**Retorna:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame. Leitura/Gravação String.

**Retorna:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Retorna ou define o nome de um arquivo de áudio que está vinculado a um AudioFrame. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Retorna ou define objeto de áudio incorporado. Leitura/Gravação [IAudio](../../com.aspose.slides/iaudio).

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Retorna ou define objeto de áudio incorporado. Leitura/Gravação [IAudio](../../com.aspose.slides/iaudio).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Especifica a duração de tempo para o fade-in inicial da mídia em milissegundos. Leitura/Gravação float.

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
public final void setFadeInDuration(float value)
```

Especifica a duração de tempo para o fade-in inicial da mídia em milissegundos. Leitura/Gravação float.

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
public final float getFadeOutDuration()
```

Especifica a duração de tempo para o fade-out final da mídia em milissegundos. Leitura/Gravação float.

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
public final void setFadeOutDuration(float value)
```

Especifica a duração de tempo para o fade-out final da mídia em milissegundos. Leitura/Gravação float.

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
public final float getVolumeValue()
```

Retorna ou define o volume do áudio em porcentagens. Leitura/Gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Define o volume do áudio para 85%
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
public final void setVolumeValue(float value)
```

Retorna ou define o volume do áudio em porcentagens. Leitura/Gravação float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Define o volume do áudio para 85%
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
public final float getTrimFromStart()
```

Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. Leitura/Gravação float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o tempo de corte inicial de 1,5 segundos
>      audioFrame.setTrimFromStart(1500f);
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

Especifica a duração de tempo a ser removida do início da mídia durante a reprodução, em milissegundos. Leitura/Gravação float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o tempo de corte inicial de 1,5 segundos
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
public final float getTrimFromEnd()
```

Especifica a duração de tempo a ser removida do fim da mídia durante a reprodução, em milissegundos. Leitura/Gravação float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o tempo de corte final 2 segundos
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Especifica a duração de tempo a ser removida do fim da mídia durante a reprodução, em milissegundos. Leitura/Gravação float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Defina o tempo de corte final de 2 segundos
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
public final ICaptionsCollection getCaptionTracks()
```

Obtém a coleção de legendas fechadas associadas ao quadro de áudio. Esta propriedade é somente leitura e retorna um [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contendo todas as faixas de legenda.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (shape instanceof IAudioFrame)
>          {
>              IAudioFrame audioFrame = (IAudioFrame) shape;
>              // Salve os dados binários da faixa de legenda como um arquivo .vtt
>              for (ICaptions captionTrack : audioFrame.getCaptionTracks()) {
>                  FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                  fos.write(captionTrack.getBinaryData());
>                  fos.close();
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)