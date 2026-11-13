---
title: IVideoFrame
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un clip vidéo sur une diapositive.
type: docs
url: /fr/com.aspose.slides/ivideoframe/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Représente un clip vidéo sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Détermine si une vidéo est automatiquement rembobinée au début dès que le film a terminé de jouer. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Détermine si une vidéo est automatiquement rembobinée au début dès que le film a terminé de jouer. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Détermine si une vidéo est en boucle. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Détermine si une vidéo est en boucle. |
| [getHideAtShowing()](#getHideAtShowing--) | Détermine si un VideoFrame est masqué. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Détermine si un VideoFrame est masqué. |
| [getVolume()](#getVolume--) | Renvoie ou définit le volume audio. |
| [setVolume(int value)](#setVolume-int-) | Renvoie ou définit le volume audio. |
| [getVolumeValue()](#getVolumeValue--) | Renvoie ou définit le volume vidéo exact en pourcentage. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Renvoie ou définit le volume vidéo exact en pourcentage. |
| [getPlayMode()](#getPlayMode--) | Renvoie ou définit le mode de lecture vidéo. |
| [setPlayMode(int value)](#setPlayMode-int-) | Renvoie ou définit le mode de lecture vidéo. |
| [getFullScreenMode()](#getFullScreenMode--) | Détermine si une vidéo est affichée en plein écran. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Détermine si une vidéo est affichée en plein écran. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie ou définit le nom d'un fichier vidéo lié à un VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie ou définit le nom d'un fichier vidéo lié à un VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Renvoie ou définit l'objet vidéo intégré. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Renvoie ou définit l'objet vidéo intégré. |
| [getTrimFromStart()](#getTrimFromStart--) | Début de rognage [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Début de rognage [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Fin de rognage [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Fin de rognage [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Obtient la collection des sous-titres fermés associés à la trame audio. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Détermine si une vidéo est automatiquement rembobinée au début dès que le film a terminé de jouer. Lecture/écriture booléen.

**Renvoie:**  
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Détermine si une vidéo est automatiquement rembobinée au début dès que le film a terminé de jouer. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Détermine si une vidéo est en boucle. Lecture/écriture booléen.

**Renvoie:**  
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Détermine si une vidéo est en boucle. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Détermine si un VideoFrame est masqué. Lecture/écriture booléen.

**Renvoie:**  
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Détermine si un VideoFrame est masqué. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Renvoie ou définit le volume audio. Lecture/écriture [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Renvoie:**  
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
### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Renvoie ou définit le volume vidéo exact en pourcentage. La valeur est exprimée en pourcentage de 0 à 100. Utilisez cette propriété pour lire ou définir des valeurs de volume plus précises que les niveaux prédéfinis disponibles via la propriété Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Lecture/écriture  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lire le volume exact actuel et le définir à 75,5 %.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie:**  
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Renvoie ou définit le volume vidéo exact en pourcentage. La valeur est exprimée en pourcentage de 0 à 100. Utilisez cette propriété pour lire ou définir des valeurs de volume plus précises que les niveaux prédéfinis disponibles via la propriété Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Lecture/écriture  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Lire le volume exact actuel et le définir à 75,5 %.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Renvoie ou définit le mode de lecture vidéo. Lecture/écriture [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Renvoie:**  
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Renvoie ou définit le mode de lecture vidéo. Lecture/écriture [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Détermine si une vidéo est affichée en plein écran. Lecture/écriture booléen.

**Renvoie:**  
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Détermine si une vidéo est affichée en plein écran. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Renvoie ou définit le nom d'un fichier vidéo lié à un VideoFrame. Lecture/écriture String.

**Renvoie:**  
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Renvoie ou définit le nom d'un fichier vidéo lié à un VideoFrame. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Renvoie ou définit l'objet vidéo intégré. Lecture/écriture [IVideo](../../com.aspose.slides/ivideo).

**Renvoie:**  
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Renvoie ou définit l'objet vidéo intégré. Lecture/écriture [IVideo](../../com.aspose.slides/ivideo).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Début de rognage [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      // définir le temps de début du rognage à 1sec
>      // définir le temps de fin du rognage à 2sec
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie:**  
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Début de rognage [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      // définir le temps de début du rognage à 1sec
>      videoFrame.setTrimFromStart(1000f);
>      // définir le temps de fin du rognage à 2sec
>      videoFrame.setTrimFromEnd(2000f);
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

Fin de rognage [ms]

**Renvoie:**  
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Fin de rognage [ms]

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Obtient la collection des sous-titres fermés associés à la trame audio. Cette propriété est en lecture seule et renvoie un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contenant toutes les pistes de sous-titres.

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
>              // Extrait les données binaires des sous-titres et les enregistre dans le fichier
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie:**  
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)