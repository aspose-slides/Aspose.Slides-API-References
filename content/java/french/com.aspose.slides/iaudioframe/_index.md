---
title: IAudioFrame
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Renvoie ou définit un indice de piste de démarrage. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Renvoie ou définit un indice de piste de démarrage. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Renvoie ou définit le temps de la piste de démarrage. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Renvoie ou définit le temps de la piste de démarrage. |
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
| [getRewindAudio()](#getRewindAudio--) | Détermine si un audio revient automatiquement au début après la lecture. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Détermine si un audio revient automatiquement au début après la lecture. |
| [getEmbedded()](#getEmbedded--) | Détermine si un son est intégré à une présentation. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie ou définit le nom d’un fichier audio lié à un AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie ou définit le nom d’un fichier audio lié à un AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Renvoie ou définit l’objet audio intégré. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Renvoie ou définit l’objet audio intégré. |
| [getFadeInDuration()](#getFadeInDuration--) | Spécifie la durée en millisecondes du fondu d’entrée initial du média. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Spécifie la durée en millisecondes du fondu d’entrée initial du média. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Spécifie la durée en millisecondes du fondu de sortie final du média. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Spécifie la durée en millisecondes du fondu de sortie final du média. |
| [getVolumeValue()](#getVolumeValue--) | Renvoie ou définit le volume audio en pourcents. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Renvoie ou définit le volume audio en pourcents. |
| [getTrimFromStart()](#getTrimFromStart--) | Spécifie la durée à supprimer du début du média pendant la lecture, en millisecondes. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Spécifie la durée à supprimer du début du média pendant la lecture, en millisecondes. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Spécifie la durée à supprimer de la fin du média pendant la lecture, en millisecondes. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Spécifie la durée à supprimer de la fin du média pendant la lecture, en millisecondes. |
| [getCaptionTracks()](#getCaptionTracks--) | Obtient la collection des sous-titres fermés associés à l’audio frame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Renvoie ou définit un indice de piste de démarrage. Lecture/écriture int.

**Renvoie :**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Renvoie ou définit un indice de piste de démarrage. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Renvoie ou définit le temps de la piste de démarrage. Lecture/écriture int.

**Renvoie :**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Renvoie ou définit le temps de la piste de démarrage. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Renvoie ou définit un indice de dernière piste Lecture/écriture int.

**Renvoie :**
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

**Renvoie :**
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

**Renvoie :**
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

**Renvoie :**
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

**Renvoie :**
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

**Renvoie :**
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
>       // Configurer l'audio pour qu'il soit lu sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurer l'audio pour qu'il revienne automatiquement au début après la lecture
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Renvoie :**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Détermine si un audio est lu sur plusieurs diapositives. Lecture/écriture boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurer l'audio pour qu'il soit lu sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurer l'audio pour qu'il revienne automatiquement au début après la lecture
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Détermine si un audio revient automatiquement au début après la lecture. Lecture/écriture boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurer l'audio pour qu'il soit lu sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurer l'audio pour qu'il revienne automatiquement au début après la lecture
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Renvoie :**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Détermine si un audio revient automatiquement au début après la lecture. Lecture/écriture boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Configurer l'audio pour qu'il soit lu sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Configurer l'audio pour qu'il revienne automatiquement au début après la lecture
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Détermine si un son est intégré à une présentation. Lecture seule boolean.

**Renvoie :**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Renvoie ou définit le nom d’un fichier audio lié à un AudioFrame. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Renvoie ou définit le nom d’un fichier audio lié à un AudioFrame. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Renvoie ou définit l’objet audio intégré. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Renvoie ou définit l’objet audio intégré. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Spécifie la durée en millisecondes du fondu d’entrée initial du média. Lecture/écriture float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir la durée du fondu d'entrée initial à 200 ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Spécifie la durée en millisecondes du fondu d’entrée initial du média. Lecture/écriture float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir la durée du fondu de démarrage à 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Spécifie la durée en millisecondes du fondu de sortie final du média. Lecture/écriture float.

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


**Renvoie :**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Spécifie la durée en millisecondes du fondu de sortie final du média. Lecture/écriture float.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
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

**Renvoie :**
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Spécifie la durée à supprimer du début du média pendant la lecture, en millisecondes. Lecture/écriture float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de découpage de début à 1,5 seconde
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Spécifie la durée à supprimer du début du média pendant la lecture, en millisecondes. Lecture/écriture float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de découpage de début à 1,5 seconde
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Spécifie la durée à supprimer de la fin du média pendant la lecture, en millisecondes. Lecture/écriture float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de découpage de fin à 2 secondes
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Spécifie la durée à supprimer de la fin du média pendant la lecture, en millisecondes. Lecture/écriture float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de découpage de fin à 2 secondes
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Obtient la collection des sous-titres fermés associés à l’audio frame. Cette propriété est lecture seule et renvoie un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contenant toutes les pistes de sous-titres.

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
>             // Enregistrer les données binaires de la piste de sous-titres en tant que fichier .vtt
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

**Renvoie :**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)