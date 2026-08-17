---
title: IAudioFrame
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει ένα ηχητικό απόσπασμα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/iaudioframe/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Αντιπροσωπεύει ένα ηχητικό απόσπασμα σε μια διαφάνεια.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Επιστρέφει ή ορίζει χρόνο αρχικού κομματιού. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Επιστρέφει ή ορίζει χρόνο αρχικού κομματιού. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Επιστρέφει ή ορίζει έναν δείκτη τελευταίου κομματιού. Ανάγνωση/εγγραφή int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Επιστρέφει ή ορίζει έναν δείκτη τελευταίου κομματιού. Ανάγνωση/εγγραφή int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Επιστρέφει ή ορίζει χρόνο τελευταίου κομματιού. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Επιστρέφει ή ορίζει χρόνο τελευταίου κομματιού. |
| [getVolume()](#getVolume--) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [setVolume(int value)](#setVolume-int-) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [getPlayMode()](#getPlayMode--) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. |
| [setPlayMode(int value)](#setPlayMode-int-) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. |
| [getHideAtShowing()](#getHideAtShowing--) | Καθορίζει εάν ένα AudioFrame είναι κρυφό. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Καθορίζει εάν ένα AudioFrame είναι κρυφό. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Καθορίζει εάν ένα ηχητικό είναι σε βρόχο. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Καθορίζει εάν ένα ηχητικό είναι σε βρόχο. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Καθορίζει εάν ένα ηχητικό παίζει ανάμεσα στις διαφάνειες. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Καθορίζει εάν ένα ηχητικό παίζει ανάμεσα στις διαφάνειες. |
| [getRewindAudio()](#getRewindAudio--) | Καθορίζει εάν ένα ηχητικό επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Καθορίζει εάν ένα ηχητικό επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή. |
| [getEmbedded()](#getEmbedded--) | Καθορίζει εάν ένας ήχος είναι ενσωματωμένος σε μια παρουσίαση. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο ήχου. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο ήχου. |
| [getFadeInDuration()](#getFadeInDuration--) | Καθορίζει τη χρονική διάρκεια του αρχικού fade-in του μέσου σε χιλιοστά του δευτερολέπτου. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Καθορίζει τη χρονική διάρκεια του αρχικού fade-in του μέσου σε χιλιοστά του δευτερολέπτου. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Καθορίζει τη χρονική διάρκεια του τελικού fade-out του μέσου σε χιλιοστά του δευτερολέπτου. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Καθορίζει τη χρονική διάρκεια του τελικού fade-out του μέσου σε χιλιοστά του δευτερολέπτου. |
| [getVolumeValue()](#getVolumeValue--) | Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. |
| [getTrimFromStart()](#getTrimFromStart--) | Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [getCaptionTracks()](#getCaptionTracks--) | Αποκτά τη συλλογή των κλειστών υπότιτλων που σχετίζονται με το audio frame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Επιστρέφει ή ορίζει χρόνο αρχικού κομματιού. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Επιστρέφει ή ορίζει χρόνο αρχικού κομματιού. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Επιστρέφει ή ορίζει έναν δείκτη τελευταίου κομματιού. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Επιστρέφει ή ορίζει έναν δείκτη τελευταίου κομματιού. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Επιστρέφει ή ορίζει χρόνο τελευταίου κομματιού. Ανάγνωση/εγγραφή int.

**Επιστρέφει:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Επιστρέφει ή ορίζει χρόνο τελευταίου κομματιού. Ανάγνωση/εγγραφή int.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. Ανάγνωση/εγγραφή [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Επιστρέφει:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. Ανάγνωση/εγγραφή [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Καθορίζει εάν ένα AudioFrame είναι κρυφό. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Καθορίζει εάν ένα AudioFrame είναι κρυφό. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Καθορίζει εάν ένα ηχητικό είναι σε βρόχο. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Καθορίζει εάν ένα ηχητικό είναι σε βρόχο. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Καθορίζει εάν ένα ηχητικό παίζει ανάμεσα στις διαφάνειες. Ανάγνωση/εγγραφή boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη Πλαισίου Ήχου
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορισμός Ήχου για αναπαραγωγή σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορισμός Αυτόματης Επαναφοράς του ήχου στην αρχή μετά την αναπαραγωγή
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Επιστρέφει:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Καθορίζει εάν ένα ηχητικό παίζει ανάμεσα στις διαφάνειες. Ανάγνωση/εγγραφή boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη Πλαισίου Ήχου
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορισμός Ήχου για αναπαραγωγή σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορισμός Αυτόματης Επαναφοράς του ήχου στην αρχή μετά την αναπαραγωγή
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Καθορίζει εάν ένα ηχητικό επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή. Ανάγνωση/εγγραφή boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη Πλαισίου Ήχου
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορισμός Ήχου για αναπαραγωγή σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορισμός Αυτόματης Επαναφοράς του ήχου στην αρχή μετά την αναπαραγωγή
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Επιστρέφει:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Καθορίζει εάν ένα ηχητικό επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή. Ανάγνωση/εγγραφή boolean.

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη Πλαισίου Ήχου
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορισμός Ήχου για αναπαραγωγή σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορισμός Αυτόματης Επαναφοράς του ήχου στην αρχή μετά την αναπαραγωγή
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Καθορίζει εάν ένας ήχος είναι ενσωματωμένος σε μια παρουσίαση. Μόνο ανάγωση boolean.

**Επιστρέφει:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο ήχου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο ήχου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Καθορίζει τη χρονική διάρκεια του αρχικού fade-in του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε τη διάρκεια του αρχικού fade για 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Καθορίζει τη χρονική διάρκεια του αρχικού fade-in του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε τη διάρκεια του αρχικού fade για 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Καθορίζει τη χρονική διάρκεια του τελικού fade-out του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε τη διάρκεια του τελικού fade για 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Καθορίζει τη χρονική διάρκεια του τελικού fade-out του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε τη διάρκεια του τελικού fade για 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. Ανάγνωση/εγγραφή float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε την ένταση ήχου στο 85%
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. Ανάγνωση/εγγραφή float.

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε την ένταση ήχου στο 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε το χρόνο έναρξης περικοπής 1.5 δευτερόλεπτα
>      audioFrame.setTrimFromStart(1500f);
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

Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε τον χρόνο έναρξης περικοπής 1.5 δευτερόλεπτα
>      audioFrame.setTrimFromStart(1500f);
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

Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε το χρόνο κοπής στο τέλος 2 δευτερόλεπτα
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίστε το χρόνο κοπής στο τέλος 2 δευτερόλεπτα
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Αποκτά τη συλλογή των κλειστών υπότιτλων που σχετίζονται με το audio frame. Αυτή η ιδιότητα είναι μόνο ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) που περιέχει όλα τα κομμάτια υποτίτλων.

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
>             // Αποθηκεύστε τα δυαδικά δεδομένα του κομματιού υπότιτλου ως αρχείο .vtt
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


**Επιστρέφει:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)