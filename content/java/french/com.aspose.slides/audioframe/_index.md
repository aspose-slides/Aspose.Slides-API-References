---
title: AudioFrame
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un clip audio sur une diapositive.
type: docs
url: /fr/com.aspose.slides/audioframe/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Représente un clip audio sur une diapositive.

--------------------

> ```
> L'exemple suivant montre comment modifier les options de lecture audio.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Obtient la forme AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Définit le mode de lecture pour jouer au clic
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Définit le volume à Bas
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Définit l'audio pour jouer sur toutes les diapositives
>      audioFrame.setPlayAcrossSlides(true);
>      // Désactive la boucle pour l'audio
>      audioFrame.setPlayLoopMode(false);
>      // Masque l'AudioFrame pendant le diaporama
>      audioFrame.setHideAtShowing(true);
>      // Rembobine l'audio au début après la lecture
>      audioFrame.setRewindAudio(true);
>      // Enregistre le fichier PowerPoint sur le disque
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Renvoie ou définit un index de piste de démarrage. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Renvoie ou définit un index de piste de démarrage. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Renvoie ou définit un temps de piste de démarrage. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Renvoie ou définit un temps de piste de démarrage. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Renvoie ou définit un index de dernière piste Lecture/écriture  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Renvoie ou définit un index de dernière piste Lecture/écriture  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Renvoie ou définit un temps de dernière piste. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Renvoie ou définit un temps de dernière piste. |
| [getVolume()](#getVolume--) | Renvoie ou définit le volume audio. |
| [setVolume(int value)](#setVolume-int-) | Renvoie ou définit le volume audio. |
| [getPlayMode()](#getPlayMode--) | Renvoie ou définit le mode de lecture audio. |
| [setPlayMode(int value)](#setPlayMode-int-) | Renvoie ou définit le mode de lecture audio. |
| [getHideAtShowing()](#getHideAtShowing--) | Détermine si un AudioFrame est masqué. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Détermine si un AudioFrame est masqué. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Détermine si un audio est en boucle. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Détermine si un audio est en boucle. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Détermine si l'audio est lu sur toutes les diapositives. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Détermine si l'audio est lu sur toutes les diapositives. |
| [getRewindAudio()](#getRewindAudio--) | Détermine si l'audio est automatiquement rembobiné au début après la lecture. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Détermine si l'audio est automatiquement rembobiné au début après la lecture. |
| [getEmbedded()](#getEmbedded--) | Détermine si un son est incorporé dans une présentation. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie ou définit le nom d'un fichier audio lié à un AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie ou définit le nom d'un fichier audio lié à un AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Renvoie ou définit un objet audio incorporé. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Renvoie ou définit un objet audio incorporé. |
| [getFadeInDuration()](#getFadeInDuration--) | Spécifie la durée en millisecondes du fondu d'entrée initial du média. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Spécifie la durée en millisecondes du fondu d'entrée initial du média. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Spécifie la durée en millisecondes du fondu de sortie final du média. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Spécifie la durée en millisecondes du fondu de sortie final du média. |
| [getVolumeValue()](#getVolumeValue--) | Renvoie ou définit le volume audio en pourcentages. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Renvoie ou définit le volume audio en pourcentages. |
| [getTrimFromStart()](#getTrimFromStart--) | Spécifie la durée à retirer du début du média pendant la lecture, en millisecondes. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Spécifie la durée à retirer du début du média pendant la lecture, en millisecondes. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes. |
| [getCaptionTracks()](#getCaptionTracks--) | Obtient la collection de sous-titres fermés associés à la trame audio. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Renvoie ou définit un index de piste de démarrage. Lecture/écriture  int .

**Renvoie :**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Renvoie ou définit un index de piste de démarrage. Lecture/écriture  int .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Renvoie ou définit un temps de piste de démarrage. Lecture/écriture  int .

**Renvoie :**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrack(int value)
```

Renvoie ou définit un temps de piste de démarrage. Lecture/écriture  int .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Renvoie ou définit un index de dernière piste Lecture/écriture  int .

**Renvoie :**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Renvoie ou définit un index de dernière piste Lecture/écriture  int .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Renvoie ou définit un temps de dernière piste Lecture/écriture  int .

**Renvoie :**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Renvoie ou définit un temps de dernière piste Lecture/écriture  int .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Renvoie ou définit le volume audio. Lecture/écriture [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Renvoie :**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Renvoie ou définit le volume audio. Lecture/écriture [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Renvoie ou définit le mode de lecture audio. Lecture/écriture [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Renvoie :**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Renvoie ou définit le mode de lecture audio. Lecture/écriture [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Détermine si un AudioFrame est masqué. Lecture/écriture  boolean .

**Renvoie :**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Détermine si un AudioFrame est masqué. Lecture/écriture  boolean .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Détermine si un audio est en boucle. Lecture/écriture  boolean .

**Renvoie :**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Détermine si un audio est en boucle. Lecture/écriture  boolean .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Détermine si l'audio est lu sur toutes les diapositives. Lecture/écriture  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Définir l'audio pour jouer sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Définir l'audio pour rembobiner automatiquement au début après la lecture
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
public final void setPlayAcrossSlides(boolean value)
```

Détermine si l'audio est lu sur toutes les diapositives. Lecture/écriture  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Définir l'audio pour jouer sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Définir l'audio pour rembobiner automatiquement au début après la lecture
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
public final boolean getRewindAudio()
```

Détermine si l'audio est automatiquement rembobiné au début après la lecture. Lecture/écriture  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Définir l'audio pour jouer sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Définir l'audio pour rembobiner automatiquement au début après la lecture
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
public final void setRewindAudio(boolean value)
```

Détermine si l'audio est automatiquement rembobiné au début après la lecture. Lecture/écriture  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Ajouter une trame audio
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Définir l'audio pour jouer sur toutes les diapositives
>       audioFrame.setPlayAcrossSlides(true);
>       // Définir l'audio pour rembobiner automatiquement au début après la lecture
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
public final boolean getEmbedded()
```

Détermine si un son est incorporé dans une présentation. Lecture seule  boolean .

**Renvoie :**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Renvoie ou définit le nom d'un fichier audio lié à un AudioFrame. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Renvoie ou définit le nom d'un fichier audio lié à un AudioFrame. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Renvoie ou définit un objet audio incorporé. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Renvoie ou définit un objet audio incorporé. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Spécifie la durée en millisecondes du fondu d'entrée initial du média. Lecture/écriture float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir la durée du fondu d'entrée à 200ms
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
public final void setFadeInDuration(float value)
```

Spécifie la durée en millisecondes du fondu d'entrée initial du média. Lecture/écriture float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir la durée du fondu d'entrée à 200ms
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
public final float getFadeOutDuration()
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
public final void setFadeOutDuration(float value)
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
public final float getVolumeValue()
```

Renvoie ou définit le volume audio en pourcentages. Lecture/écriture float.

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
public final void setVolumeValue(float value)
```

Renvoie ou définit le volume audio en pourcentages. Lecture/écriture float.

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
public final float getTrimFromStart()
```

Spécifie la durée à retirer du début du média pendant la lecture, en millisecondes. Lecture/écriture float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de coupe de début à 1,5 seconde
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Spécifie la durée à retirer du début du média pendant la lecture, en millisecondes. Lecture/écriture float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de coupe de début à 1,5 seconde
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
public final float getTrimFromEnd()
```

Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes. Lecture/écriture float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de coupe de fin à 2 secondes
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes. Lecture/écriture float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Définir le temps de coupe de fin à 2 secondes
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
public final ICaptionsCollection getCaptionTracks()
```

Obtient la collection de sous-titres fermés associés à la trame audio. Cette propriété est lecture seule et renvoie un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contenant toutes les pistes de sous-titres.

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
>              // Enregistrer les données binaires de la piste de sous-titres dans un fichier .vtt
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

**Renvoie :**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)