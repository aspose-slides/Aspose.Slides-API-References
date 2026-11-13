---
title: IVideoFrame
second_title: Aspose.Slides για την τεκμηρίωση API της Java
description: Αναπαριστά ένα βίντεο σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/ivideoframe/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Αναπαριστά ένα βίντεο σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Καθορίζει αν ένα βίντεο επανέρχεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή του. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Καθορίζει αν ένα βίντεο επανέρχεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή του. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Καθορίζει αν ένα βίντεο επαναλαμβάνεται σε βρόχο. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Καθορίζει αν ένα βίντεο επαναλαμβάνεται σε βρόχο. |
| [getHideAtShowing()](#getHideAtShowing--) | Καθορίζει αν ένα VideoFrame είναι κρυφό. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Καθορίζει αν ένα VideoFrame είναι κρυφό. |
| [getVolume()](#getVolume--) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [setVolume(int value)](#setVolume-int-) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [getVolumeValue()](#getVolumeValue--) | Επιστρέφει ή ορίζει την ακριβή ένταση βίντεο ως ποσοστό. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Επιστρέφει ή ορίζει την ακριβή ένταση βίντεο ως ποσοστό. |
| [getPlayMode()](#getPlayMode--) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. |
| [setPlayMode(int value)](#setPlayMode-int-) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. |
| [getFullScreenMode()](#getFullScreenMode--) | Καθορίζει αν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθόνης. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Καθορίζει αν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθόνης. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που συνδέεται με ένα VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που συνδέεται με ένα VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. |
| [getTrimFromStart()](#getTrimFromStart--) | Περικοπή έναρξης [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Περικοπή έναρξης [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Περικοπή λήξης [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Περικοπή λήξης [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Λαμβάνει τη συλλογή των κλειστών λεζαντών που σχετίζονται με το πλαίσιο ήχου. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Καθορίζει αν ένα βίντεο επανέρχεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή του. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Καθορίζει αν ένα βίντεο επανέρχεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή του. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Καθορίζει αν ένα βίντεο επαναλαμβάνεται σε βρόχο. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Καθορίζει αν ένα βίντεο επαναλαμβάνεται σε βρόχο. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Καθορίζει αν ένα VideoFrame είναι κρυφό. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Καθορίζει αν ένα VideoFrame είναι κρυφό. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Επιστρέφει ή ορίζει την ένταση ήχου. Ανάγνωση/εγγραφή [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returns:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Επιστρέφει ή ορίζει την ένταση ήχου. Ανάγνωση/εγγραφή [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Επιστρέφει ή ορίζει την ακριβή ένταση βίντεο ως ποσοστό. Η τιμή εκφράζεται ως ποσοστό από 0 έως 100. Χρησιμοποιήστε αυτήν την ιδιότητα για να διαβάσετε ή να ορίσετε τιμές έντασης που είναι πιο ακριβείς από τα προκαθορισμένα επίπεδα που διατίθενται μέσω της ιδιότητας Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Ανάγνωση/εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Διαβάστε την τρέχουσα ακριβή ένταση και ορίστε την στο 75.5 τοις εκατό.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
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

Επιστρέφει ή ορίζει την ακριβή ένταση βίντεο ως ποσοστό. Η τιμή εκφράζεται ως ποσοστό από 0 έως 100. Χρησιμοποιήστε αυτήν την ιδιότητα για να διαβάσετε ή να ορίσετε τιμές έντασης που είναι πιο ακριβείς από τα προκαθορισμένα επίπεδα που διατίθενται μέσω της ιδιότητας Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Ανάγνωση/εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Διαβάστε την τρέχουσα ακριβή ένταση και ορίστε την στο 75.5 τοις εκατό.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. Ανάγνωση/εγγραφή [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Returns:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. Ανάγνωση/εγγραφή [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Καθορίζει αν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθόνης. Ανάγνωση/εγγραφή boolean.

**Returns:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Καθορίζει αν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθάννης. Ανάγνωση/εγγραφή boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που συνδέεται με ένα VideoFrame. Ανάγνωση/εγγραφή String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που συνδέεται με ένα VideoFrame. Ανάγνωση/εγγραφή String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. Ανάγνωση/εγγραφή [IVideo](../../com.aspose.slides/ivideo).

**Returns:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. Ανάγνωση/εγγραφή [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Περικοπή έναρξης [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ορίστε τον χρόνο έναρξης περικοπής σε 1 δευτερόλεπτο
>      videoFrame.setTrimFromStart(1000f);
>      //ορίστε τον χρόνο λήξης περικοπής σε 2 δευτερόλεπτα
>      videoFrame.setTrimFromEnd(2000f);
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

Περικοπή έναρξης [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ορίστε χρόνο έναρξης περικοπής 1 δευτερόλεπτο
>      videoFrame.setTrimFromStart(1000f);
>      //ορίστε χρόνο λήξης περικοπής 2 δευτερόλεπτα
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
public abstract float getTrimFromEnd()
```

Περικοπή λήξης [ms]

**Returns:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Περικοπή λήξης [ms]

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Λαμβάνει τη συλλογή των κλειστών λεζαντών που σχετίζονται με το πλαίσιο ήχου. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) που περιέχει όλα τα κομμάτια λεζαντών.

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
>              // Εξάγει τα δυαδικά δεδομένα των λεζαντών και τα αποθηκεύει στο αρχείο
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