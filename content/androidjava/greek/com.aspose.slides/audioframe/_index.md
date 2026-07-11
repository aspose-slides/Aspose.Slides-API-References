---
title: AudioFrame
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει ένα ηχητικό κλιπ σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/audioframe/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Αναπαριστά ένα ηχητικό κλιπ σε μια διαφάνεια.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Λαμβάνει το σχήμα AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Ορίζει τη λειτουργία αναπαραγωγής ώστε να παίζει με κλικ
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Ορίζει την ένταση σε Low
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
>      audioFrame.setPlayAcrossSlides(true);
>      // Απενεργοποιεί την επανάληψη για τον ήχο
>      audioFrame.setPlayLoopMode(false);
>      // Κρύβει το AudioFrame κατά τη διάρκεια της παρουσίασης
>      audioFrame.setHideAtShowing(true);
>      // Επαναφέρει τον ήχο στην αρχή μετά την αναπαραγωγή
>      audioFrame.setRewindAudio(true);
>      // Αποθηκεύει το αρχείο PowerPoint στο δίσκο
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Επιστρέφει ή ορίζει χρόνο έναρξης κομματιού. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Επιστρέφει ή ορίζει χρόνο έναρξης κομματιού. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Επιστρέφει ή ορίζει έναν δείκτη τελευταίου κομματιού. Ανάγνωση/Εγγραφή int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Επιστρέφει ή ορίζει έναν δείκτη τελευταίου κομματιού. Ανάγνωση/Εγγραφή int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Επιστρέφει ή ορίζει χρόνο λήξης κομματιού. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Επιστρέφει ή ορίζει χρόνο λήξης κομματιού. |
| [getVolume()](#getVolume--) | Επιστρέφει ή ορίζει την ένταση του ήχου. |
| [setVolume(int value)](#setVolume-int-) | Επιστρέφει ή ορίζει την ένταση του ήχου. |
| [getPlayMode()](#getPlayMode--) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. |
| [setPlayMode(int value)](#setPlayMode-int-) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. |
| [getHideAtShowing()](#getHideAtShowing--) | Καθορίζει εάν ένα AudioFrame είναι κρυφό. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Καθορίζει εάν ένα AudioFrame είναι κρυφό. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Καθορίζει εάν ένας ήχος επαναλαμβάνεται. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Καθορίζει εάν ένας ήχος επαναλαμβάνεται. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Καθορίζει εάν ο ήχος παίζει σε όλες τις διαφάνειες. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Καθορίζει εάν ο ήχος παίζει σε όλες τις διαφάνειες. |
| [getRewindAudio()](#getRewindAudio--) | Καθορίζει εάν ο ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Καθορίζει εάν ο ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή. |
| [getEmbedded()](#getEmbedded--) | Καθορίζει εάν ένας ήχος ενσωματώνεται στην παρουσίαση. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που συνδέεται με ένα AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που συνδέεται με ένα AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο ήχου. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Επιστρέφει ή ορίζει το ενσωματωμένο αντικείμενο ήχου. |
| [getFadeInDuration()](#getFadeInDuration--) | Καθορίζει τη διάρκεια χρόνου για το αρχικό fade-in του μέσου σε χιλιοστά του δευτερολέπτου. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Καθορίζει τη διάρκεια χρόνου για το αρχικό fade-in του μέσου σε χιλιοστά του δευτερολέπτου. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Καθορίζει τη διάρκεια χρόνου για το τελικό fade-out του μέσου σε χιλιοστά του δευτερολέπτου. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Καθορίζει τη διάρκεια χρόνου για το τελικό fade-out του μέσου σε χιλιοστά του δευτερολέπτου. |
| [getVolumeValue()](#getVolumeValue--) | Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. |
| [getTrimFromStart()](#getTrimFromStart--) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [getCaptionTracks()](#getCaptionTracks--) | Λαμβάνει τη συλλογή των κλειστών λεζαντών που σχετίζονται με το πλαίσιο ήχου. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού. Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού. Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Επιστρέφει ή ορίζει χρόνο έναρξης κομματιού. Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Επιστρέφει ή ορίζει χρόνο έναρξης κομματιού. Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Επιστρέφει ή ορίζει έναν δείκτη τελευταίου κομματιού. Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Επιστρέφει ή ορίζει έναν δείκτη τελευταίου κομματιού. Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Επιστρέφει ή ορίζει χρόνο λήξης κομματιού. Ανάγνωση/Εγγραφή int.

**Επιστρέφει:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Επιστρέφει ή ορίζει χρόνο λήξης κομματιού. Ανάγνωση/Εγγραφή int.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Επιστρέφει ή ορίζει την ένταση του ήχου. Ανάγνωση/Εγγραφή [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Επιστρέφει:**
int
### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Επιστρέφει ή ορίζει την ένταση του ήχου. Ανάγνωση/Εγγραφή [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. Ανάγνωση/Εγγραφή [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Επιστρέφει:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. Ανάγνωση/Εγγραφή [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Καθορίζει εάν ένα AudioFrame είναι κρυφό. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Καθορίζει εάν ένα AudioFrame είναι κρυφό. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Καθορίζει εάν ένας ήχος επαναλαμβάνεται. Ανάγνωση/Εγγραφή boolean.

**Επιστρέφει:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Καθορίζει εάν ένας ήχος επαναλαμβάνεται. Ανάγνωση/Εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Καθορίζει εάν ο ήχος παίζει σε όλες τις διαφάνειες. Ανάγνωση/Εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη πλαισίου ήχου
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορίζει τον ήχο να επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή
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
public final void setPlayAcrossSlides(boolean value)
```

Καθορίζει εάν ο ήχος παίζει σε όλες τις διαφάνειες. Ανάγνωση/Εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη πλαισίου ήχου
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορίζει τον ήχο να επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

Καθορίζει εάν ο ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή. Ανάγνωση/Εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη πλαισίου ήχου
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορίζει τον ήχο να επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή
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
public final void setRewindAudio(boolean value)
```

Καθορίζει εάν ο ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή. Ανάγνωση/Εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη πλαισίου ήχου
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορίζει τον ήχο να επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

Καθορίζει εάν ένας ήχος ενσωματώνεται στην παρουσίαση. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που συνδέεται με ένα AudioFrame. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που συνδέεται με ένα AudioFrame. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο ήχου. Ανάγνωση/Εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο ήχου. Ανάγνωση/Εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Καθορίζει τη διάρκεια χρόνου για το αρχικό fade-in του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τη διάρκεια του αρχικού fade στα 200ms
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
public final void setFadeInDuration(float value)
```

Καθορίζει τη διάρκεια χρόνου για το αρχικό fade-in του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τη διάρκεια του αρχικού fade στα 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

Καθορίζει τη διάρκεια χρόνου για το τελικό fade-out του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τη διάρκεια του τελικού fade για 500ms
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
public final void setFadeOutDuration(float value)
```

Καθορίζει τη διάρκεια χρόνου για το τελικό fade-out του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τη διάρκεια του τελικού fade για 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει την ένταση ήχου στο 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει την ένταση ήχου στο 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει το χρόνο έναρξης περικοπής 1.5 δευτερόλεπτα
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει το χρόνο έναρξης περικοπής 1.5 δευτερόλεπτα
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει το χρόνο λήξης περικοπής 2 δευτερόλεπτα
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/Εγγραφή float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει το χρόνο λήξης περικοπής 2 δευτερόλεπτα
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

Λαμβάνει τη συλλογή των κλειστών λεζαντών που σχετίζονται με το πλαίσιο ήχου. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) που περιέχει όλα τα κομμάτια λεζαντών.

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
>              // Αποθηκεύει τα δυαδικά δεδομένα του κομματιού λεζάντας ως αρχείο .vtt
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

**Επιστρέφει:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)