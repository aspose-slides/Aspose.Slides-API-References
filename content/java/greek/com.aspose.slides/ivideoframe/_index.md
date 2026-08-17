---
title: IVideoFrame
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει ένα απόσπασμα βίντεο σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/ivideoframe/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Αντιπροσωπεύει ένα απόσπασμα βίντεο σε μια διαφάνεια.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Καθορίζει εάν ένα βίντεο επαναφέρεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή της ταινίας. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Καθορίζει εάν ένα βίντεο επαναφέρεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή της ταινίας. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Καθορίζει εάν ένα βίντεο επαναλαμβάνεται. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Καθορίζει εάν ένα βίντεο επαναλαμβάνεται. |
| [getHideAtShowing()](#getHideAtShowing--) | Καθορίζει εάν ένα VideoFrame είναι κρυφό. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Καθορίζει εάν ένα VideoFrame είναι κρυφό. |
| [getVolume()](#getVolume--) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [setVolume(int value)](#setVolume-int-) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [getPlayMode()](#getPlayMode--) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. |
| [setPlayMode(int value)](#setPlayMode-int-) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. |
| [getFullScreenMode()](#getFullScreenMode--) | Καθορίζει εάν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθόνης. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Καθορίζει εάν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθόνης. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που είναι συνδεδεμένο με ένα VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που είναι συνδεδεμένο με ένα VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. |
| [getTrimFromStart()](#getTrimFromStart--) | Περικοπή από την αρχή [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Περικοπή από την αρχή [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Περικοπή από το τέλος [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Περικοπή από το τέλος [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Παίρνει τη συλλογή των κλειστών υπότιτλων που σχετίζονται με το πλαίσιο ήχου. |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Καθορίζει εάν ένα βίντεο επαναφέρεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή της ταινίας. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Καθορίζει εάν ένα βίντεο επαναφέρεται αυτόματα στην αρχή μόλις ολοκληρωθεί η αναπαραγωγή της ταινίας. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Καθορίζει εάν ένα βίντεο επαναλαμβάνεται. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Καθορίζει εάν ένα βίντεο επαναλαμβάνεται. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Καθορίζει εάν ένα VideoFrame είναι κρυφό. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Καθορίζει εάν ένα VideoFrame είναι κρυφό. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Επιστρέφει ή ορίζει την ένταση ήχου. Ανάγνωση/εγγραφή [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Επιστρέφει:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Επιστρέφει ή ορίζει την ένταση ήχου. Ανάγνωση/εγγραφή [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. Ανάγνωση/εγγραφή [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Επιστρέφει:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής βίντεο. Ανάγνωση/εγγραφή [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Καθορίζει εάν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθόνης. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Καθορίζει εάν ένα βίντεο εμφανίζεται σε λειτουργία πλήρους οθόνης. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που είναι συνδεδεμένο με ένα VideoFrame. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου βίντεο που είναι συνδεδεμένο με ένα VideoFrame. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. Ανάγνωση/εγγραφή [IVideo](../../com.aspose.slides/ivideo).

**Επιστρέφει:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο βίντεο. Ανάγνωση/εγγραφή [IVideo](../../com.aspose.slides/ivideo).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Περικοπή από την αρχή [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //set triming start time 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //set triming end time 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Περικοπή από την αρχή [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //set triming start time 1sec
>      videoFrame.setTrimFromStart(1000f);
>      //set triming end time 2sec
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Περικοπή από το τέλος [ms]

**Επιστρέφει:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Περικοπή από το τέλος [ms]

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Παίρνει τη συλλογή των κλειστών υπότιτλων που σχετίζονται με το πλαίσιο ήχου. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) που περιέχει όλες τις διαδρομές υπότιτλων.

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

**Επιστρέφει:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)