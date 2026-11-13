---
title: VideoFrame
second_title: Aspose.Slides για την Αναφορά API Java
description: Αναπαριστά ένα κλιπ βίντεο σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/videoframe/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IVideoFrame](../../com.aspose.slides/ivideoframe)
```
public class VideoFrame extends PictureFrame implements IVideoFrame
```

Αντιπροσωπεύει ένα κλιπ βίντεο σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Καθορίζει εάν το βίντεο επανέρχεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή του. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Καθορίζει εάν το βίντεο επανέρχεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή του. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Καθορίζει εάν το βίντεο επαναλαμβάνεται σε βρόχο. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Καθορίζει εάν το βίντεο επαναλαμβάνεται σε βρόχο. |
| [getHideAtShowing()](#getHideAtShowing--) | Καθορίζει εάν ένα VideoFrame είναι κρυφό. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Καθορίζει εάν ένα VideoFrame είναι κρυφό. |
| [getVolume()](#getVolume--) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [setVolume(int value)](#setVolume-int-) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [getVolumeValue()](#getVolumeValue--) | Επιστρέφει ή ορίζει την ακριβή ένταση βίντεο ως ποσοστό. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Επιστρέφει ή ορίζει την ακριβή ένταση βίντεο ως ποσοστό. |
| [getPlayMode()](#getPlayMode--) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. |
| [setPlayMode(int value)](#setPlayMode-int-) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. |
| [getFullScreenMode()](#getFullScreenMode--) | Καθορίζει εάν το βίντεο εμφανίζεται σε πλήρη οθόνη. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Καθορίζει εάν το βίντεο εμφανίζεται σε πλήρη οθόνη. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που είναι συνδεδεμένο με ένα VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που είναι συνδεδεμένο με ένα VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. |
| [getTrimFromStart()](#getTrimFromStart--) | Περικοπή έναρξης [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Περικοπή έναρξης [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Περικοπή λήξης [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Περικοπή λήξης [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Αποκτά τη συλλογή των κλειστών υπότιτλων που σχετίζονται με το πλαίσιο βίντεο. |
### getRewindVideo() {#getRewindVideo--}
```
public final boolean getRewindVideo()
```

Καθορίζει εάν το βίντεο επανέρχεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή του. Read/write boolean.

**Returns:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public final void setRewindVideo(boolean value)
```

Καθορίζει εάν το βίντεο επανέρχεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή του. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Καθορίζει εάν το βίντεο επαναλαμβάνεται σε βρόχο. Read/write boolean.

**Returns:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Καθορίζει εάν το βίντεο επαναλαμβάνεται σε βρόχο. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Καθορίζει εάν ένα VideoFrame είναι κρυφό. Read/write boolean.

**Returns:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Καθορίζει εάν ένα VideoFrame είναι κρυφό. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Επιστρέφει ή ορίζει την ένταση ήχου. Read/write [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Returns:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Επιστρέφει ή ορίζει την ένταση ήχου. Read/write [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Επιστρέφει ή ορίζει την ακριβή ένταση βίντεο ως ποσοστό. Η τιμή εκφράζεται ως ποσοστό από 0 έως 100. Χρησιμοποιήστε αυτήν την ιδιότητα για να διαβάσετε ή να ορίσετε τιμές έντασης που είναι πιο ακριβείς από τα προκαθορισμένα επίπεδα διαθέσιμα μέσω της \#getVolume.getVolume/\#setVolume(int).setVolume(int) ιδιότητας. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Διαβάστε την τρέχουσα ακριβή ένταση και ορίστε τη στο 75.5 τοις εκατό.
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
public final void setVolumeValue(float value)
```

Επιστρέφει ή ορίζει την ακριβή ένταση βίντεο ως ποσοστό. Η τιμή εκφράζεται ως ποσοστό από 0 έως 100. Χρησιμοποιήστε αυτήν την ιδιότητα για να διαβάσετε ή να ορίσετε τιμές έντασης που είναι πιο ακριβείς από τα προκαθορισμένα επίπεδα διαθέσιμα μέσω της \#getVolume.getVolume/\#setVolume(int).setVolume(int) ιδιότητας. Read/write float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Διαβάστε την τρέχουσα ακριβή ένταση και ορίστε τη στο 75.5 τοις εκατό.
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
public final int getPlayMode()
```

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. Read/write [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Returns:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. Read/write [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public final boolean getFullScreenMode()
```

Καθορίζει εάν το βίντεο εμφανίζεται σε πλήρη οθόνη. Read/write boolean.

**Returns:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public final void setFullScreenMode(boolean value)
```

Καθορίζει εάν το βίντεο εμφανίζεται σε πλήρη οθόνη. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που είναι συνδεδεμένο με ένα VideoFrame. Read/write String.

**Returns:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που είναι συνδεδεμένο με ένα VideoFrame. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public final IVideo getEmbeddedVideo()
```

Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. Read/write [IVideo](../../com.aspose.slides/ivideo).

**Returns:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public final void setEmbeddedVideo(IVideo value)
```

Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. Read/write [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
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
>      //ορίστε την έναρξη κοπής 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //ορίστε το τέλος κοπής 2sec
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
>      //ορίστε την έναρξη κοπής 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //ορίστε το τέλος κοπής 2sec
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

Περικοπή λήξης [ms]

**Returns:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Περικοπή λήξης [ms]

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Αποκτά τη συλλογή των κλειστών υπότιτλων που σχετίζονται με το πλαίσιο βίντεο. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) που περιέχει όλα τα κομμάτια υπότιτλων.

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
>              // Εξάγει τα δυαδικά δεδομένα των υπότιτλων και τα αποθηκεύει στο αρχείο
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