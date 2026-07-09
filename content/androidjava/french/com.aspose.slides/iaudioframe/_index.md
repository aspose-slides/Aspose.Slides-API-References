---
title: IAudioFrame
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un extrait audio sur une diapositive.
type: docs
url: /fr/com.aspose.slides/iaudioframe/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Représente un extrait audio sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Renvoie ou définit un indice de piste de départ. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Renvoie ou définit un indice de piste de départ. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Renvoie ou définit le temps de piste de départ. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Renvoie ou définit le temps de piste de départ. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Renvoie ou définit un indice de dernière piste Lecture/écriture int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Renvoie ou définit un indice de dernière piste Lecture/écriture int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Renvoie ou définit le temps de la dernière piste. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Renvoie ou définit le temps de la dernière piste. |
| [getVolume()](#getVolume--) | Renvoie ou définit le volume audio. |
| [setVolume(int value)](#setVolume-int-) | Renvoie ou définit le volume audio. |
| [getPlayMode()](#getPlayMode--) | Renvoie ou définit le mode de lecture audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Renvoie ou définit le mode de lecture audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Détermine si un AudioFrame est masqué. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Détermine si un AudioFrame est masqué. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Détermine si un audio est en boucle. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Détermine si un audio est en boucle. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Détermine si un audio est lu sur plusieurs diapositives. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Détermine si un audio est lu sur plusieurs diapositives. |
| [getRewindAudio()](#getRewindAudio--) | Détermine si un audio est automatiquement rembobiné au début après la lecture. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Détermine si un audio est automatiquement rembobiné au début après la lecture. |
| [getEmbedded()](#getEmbedded--) | Détermine si un son est intégré à une présentation. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie ou définit le nom d'un fichier audio lié à un AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie ou définit le nom d'un fichier audio lié à un AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Renvoie ou définit l'objet audio intégré. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Renvoie ou définit l'objet audio intégré. |
| [getFadeInDuration()](#getFadeInDuration--) | Spécifie la durée en millisecondes du fondu en entrée initial du média. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Spécifie la durée en millisecondes du fondu en entrée initial du média. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Spécifie la durée en millisecondes du fondu en sortie final du média. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Spécifie la durée en millisecondes du fondu en sortie final du média. |
| [getVolumeValue()](#getVolumeValue--) | Renvoie ou définit le volume audio en pourcents. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Renvoie ou définit le volume audio en pourcents. |
| [getTrimFromStart()](#getTrimFromStart--) | Spécifie la durée à supprimer du début du média lors de la lecture, en millisecondes. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Spécifie la durée à supprimer du début du média lors de la lecture, en millisecondes. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Spécifie la durée à supprimer de la fin du média lors de la lecture, en millisecondes. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Spécifie la durée à supprimer de la fin du média lors de la lecture, en millisecondes. |
| [getCaptionTracks()](#getCaptionTracks--) | Obtient la collection de sous-titres associés à la trame audio. |
### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Renvoie ou définit un indice de piste de départ. Lecture/écriture int.

**Retour :**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Renvoie ou définit un indice de piste de départ. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Renvoie ou définit le temps de piste de départ. Lecture/écriture int.

**Retour :**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Renvoie ou définit le temps de piste de départ. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Renvoie ou définit un indice de dernière piste Lecture/écriture int.

**Retour :**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Renvoie ou définit un indice de dernière piste Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Renvoie ou définit le temps de la dernière piste. Lecture/écriture int.

**Retour :**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Renvoie ou définit le temps de la dernière piste. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Renvoie ou définit le volume audio. Lecture/écriture [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Retour :**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Renvoie ou définit le volume audio. Lecture/écriture [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Renvoie ou définit le mode de lecture audio. Lecture/écriture [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Retour :**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Renvoie ou définit le mode de lecture audio. Lecture/écriture [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Détermine si un AudioFrame est masqué. Lecture/écriture boolean.

**Retour :**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Détermine si un AudioFrame est masqué. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Détermine si un audio est en boucle. Lecture/écriture boolean.

**Retour :**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Détermine si un audio est en boucle. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Détermine si un audio est lu sur plusieurs diapositives. Lecture/écriture boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Définir l'audio pour qu'il se joue sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurer l'audio pour qu'il rembobine automatiquement au début après la lecture
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Returns:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Determines whether an audio is playing across the slides. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Définir l'audio pour qu'il se joue sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurer l'audio pour qu'il rembobine automatiquement au début après la lecture
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Determines whether an audio is automatically rewinded to start after playing. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Définir l'audio pour qu'il se joue sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurer l'audio pour qu'il rembobine automatiquement au début après la lecture
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Returns:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Determines whether an audio is automatically rewinded to start after playing. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Définir l'audio pour qu'il se joue sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurer l'audio pour qu'il rembobine automatiquement au début après la lecture
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Determines whether a sound is embedded to a presentation. Read-only boolean.

**Returns:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Returns or sets the name of an audio file which is linked to an AudioFrame. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Returns or sets embedded audio object. Read/write [IAudio](../../com.aspose.slides/iaudio).

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Renvoie ou définit l'objet audio intégré. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Specifies the time duration for the initial fade-in of the media in milliseconds. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définit la durée du fondu de démarrage à 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Specifies the time duration for the initial fade-in of the media in milliseconds. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définit la durée du fondu de démarrage à 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
```
public abstract float getFadeOutDuration()
```

Specifies the time duration for the ending fade-out of the media in milliseconds. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir la durée du fondu de sortie à 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Specifies the time duration for the ending fade-out of the media in milliseconds. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir la durée du fondu de sortie à 500 ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Returns or sets the audio volume in percents. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le volume audio à 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Renvoie ou définit le volume audio en pourcents. Lecture/écriture float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le volume audio à 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```
Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Read/write float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de rognage de départ à 1,5 seconde
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```
Specifies the time duration to be removed from the beginning of the media during playback, in milliseconds. Read/write float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de rognage de départ à 1,5 seconde
>      audioFrame.setTrimFromStart(1500f);
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
public abstract float getTrimFromEnd()
```
Specifies the time duration to be removed from the end of the media during playback, in milliseconds. Read/write float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de rognage de fin à 2 secondes
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```
Specifies the time duration to be removed from the end of the media during playback, in milliseconds. Read/write float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Set the end trimming time 2 seconds
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()


Obtient la collection de sous-titres associés à la trame audio. Cette propriété est en lecture seule et renvoie un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contenant toutes les pistes de sous-titres.

--------------------

> ```
> Exemple :
>  
>  Presentation pres = new Presentation("audio with captions.pptx");
>  try {
>     for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>     {
>         if (shape instanceof IAudioFrame)
>         {
>             IAudioFrame audioFrame = (IAudioFrame) shape;
>             // Save the caption track's binary data as a .vtt file
>             for (ICaptions captionTrack : audioFrame.getCaptionTracks())
>             {
>                 FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>                 fos.write(captionTrack.getBinaryData());
>                 fos.close();
>             }
>         }
>     }
> } finally {
>      if (pres != null) pres.dispose();
> }
> ```

**Retour :**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)