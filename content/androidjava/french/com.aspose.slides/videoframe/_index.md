---
title: VideoFrame
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un clip vidéo sur une diapositive.
type: docs
url: /fr/com.aspose.slides/videoframe/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Représente un clip vidéo sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Détermine si une vidéo est automatiquement rembobinée au début dès que le film a fini de jouer. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Détermine si une vidéo est automatiquement rembobinée au début dès que le film a fini de jouer. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Détermine si une vidéo est en boucle. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Détermine si une vidéo est en boucle. |
| [getHideAtShowing()](#getHideAtShowing--) | Détermine si un VideoFrame est masqué. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Détermine si un VideoFrame est masqué. |
| [getVolume()](#getVolume--) | Renvoie ou définit le volume audio. |
| [setVolume(int value)](#setVolume-int-) | Renvoie ou définit le volume audio. |
| [getPlayMode()](#getPlayMode--) | Renvoie ou définit le mode de lecture vidéo. |
| [setPlayMode(int value)](#setPlayMode-int-) | Renvoie ou définit le mode de lecture vidéo. |
| [getFullScreenMode()](#getFullScreenMode--) | Détermine si une vidéo est affichée en plein écran. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Détermine si une vidéo est affichée en plein écran. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie ou définit le nom d'un fichier vidéo lié à un VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie ou définit le nom d'un fichier vidéo lié à un VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Renvoie ou définit l'objet vidéo intégré. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Renvoie ou définit l'objet vidéo intégré. |
| [getTrimFromStart()](#getTrimFromStart--) | Début du rognage [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Début du rognage [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Fin du rognage [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Fin du rognage [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Obtient la collection des sous-titres fermés associés à la trame vidéo. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Détermine si une vidéo est automatiquement rembobinée au début dès que le film a fini de jouer. Lecture/écriture booléen.

**Renvoie :**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Détermine si une vidéo est automatiquement rembobinée au début dès que le film a fini de jouer. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Détermine si une vidéo est en boucle. Lecture/écriture booléen.

**Renvoie :**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Détermine si une vidéo est en boucle. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Détermine si un VideoFrame est masqué. Lecture/écriture booléen.

**Renvoie :**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Détermine si un VideoFrame est masqué. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
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

Renvoie ou définit le mode de lecture vidéo. Lecture/écriture [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Renvoie :**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Renvoie ou définit le mode de lecture vidéo. Lecture/écriture [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Détermine si une vidéo est affichée en plein écran. Lecture/écriture booléen.

**Renvoie :**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Détermine si une vidéo est affichée en plein écran. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Renvoie ou définit le nom d'un fichier vidéo lié à un VideoFrame. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Renvoie ou définit le nom d'un fichier vidéo lié à un VideoFrame. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Renvoie ou définit l'objet vidéo intégré. Lecture/écriture [IVideo](../../com.aspose.slides/ivideo).

**Renvoie :**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Renvoie ou définit l'objet vidéo intégré. Lecture/écriture [IVideo](../../com.aspose.slides/ivideo).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Début du rognage [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //définir le temps de début du rognage à 1 sec
>      videoFrame.setTrimFromStart(1000f);
>      //définir le temps de fin du rognage à 2 sec
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

Trim start [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //définir le temps de début du rognage à 1 sec
>      videoFrame.setTrimFromStart(1000f);
>      //définir le temps de fin du rognage à 2 sec
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

Trim end [ms]

**Returns:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Trim end [ms]

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()


Obtient la collection des sous-titres fermés associés à la trame vidéo. Cette propriété est en lecture seule et renvoie un [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) contenant toutes les pistes de sous-titres.

--------------------

> ```
> Exemple :
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
>              // Extracts the captions binary data and saves them to the file
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)