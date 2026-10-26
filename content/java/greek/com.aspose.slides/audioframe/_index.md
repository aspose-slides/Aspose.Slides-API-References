---
title: AudioFrame
second_title: Aspose.Slides για Java Αναφορά API
description: Αναπαριστά ένα ηχητικό απόσπασμα σε μια διαφάνεια.
type: docs
url: /el/com.aspose.slides/audioframe/
---
**Κληρονόμηση:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Αναπαριστά ένα ηχητικό απόσπασμα σε μια διαφάνεια.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Λαμβάνει το σχήμα AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Ορίζει τη λειτουργία αναπαραγωγής για να παίζει κατά κλικ
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Ορίζει την ένταση σε χαμηλή
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
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Επιστρέφει ή ορίζει έναν τελικό δείκτη κομματιού. Ανάγνωση/εγγραφή  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Επιστρέφει ή ορίζει έναν τελικό δείκτη κομματιού. Ανάγνωση/εγγραφή  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Επιστρέφει ή ορίζει χρόνο λήξης κομματιού. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Επιστρέφει ή ορίζει χρόνο λήξης κομματιού. |
| [getVolume()](#getVolume--) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [setVolume(int value)](#setVolume-int-) | Επιστρέφει ή ορίζει την ένταση ήχου. |
| [getPlayMode()](#getPlayMode--) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. |
| [setPlayMode(int value)](#setPlayMode-int-) | Επιστρέφει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. |
| [getHideAtShowing()](#getHideAtShowing--) | Καθορίζει αν ένα AudioFrame είναι κρυφό. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Καθορίζει αν ένα AudioFrame είναι κρυφό. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Καθορίζει αν ένας ήχος επαναλαμβάνεται. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Καθορίζει αν ένας ήχος επαναλαμβάνεται. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Καθορίζει αν ο ήχος παίζει διαμέσου των διαφανειών. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Καθορίζει αν ο ήχος παίζει διαμέσου των διαφανειών. |
| [getRewindAudio()](#getRewindAudio--) | Καθορίζει αν ο ήχος επαναξιουράζεται αυτόματα στην αρχή μετά την αναπαραγωγή. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Καθορίζει αν ο ήχος επαναξιουράζεται αυτόματα στην αρχή μετά την αναπαραγωγή. |
| [getEmbedded()](#getEmbedded--) | Καθορίζει αν ένας ήχος είναι ενσωματωμένος σε μια παρουσίαση. |
| [getLinkPathLong()](#getLinkPathLong--) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο ήχου. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Επιστρέφει ή ορίζει ενσωματωμένο αντικείμενο ήχου. |
| [getFadeInDuration()](#getFadeInDuration--) | Καθορίζει τη διάρκεια χρόνου για την αρχική εναφίπλωση του μέσου σε χιλιοστά του δευτερολέπτου. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Καθορίζει τη διάρκεια χρόνου για την αρχική εναφίπλωση του μέσου σε χιλιοστά του δευτερολέπτου. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Καθορίζει τη διάρκεια χρόνου για την τελική ξεθώριασμα του μέσου σε χιλιοστά του δευτερολέπτου. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Καθορίζει τη διάρκεια χρόνου για την τελική ξεθώριασμα του μέσου σε χιλιοστά του δευτερολέπτου. |
| [getVolumeValue()](#getVolumeValue--) | Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Επιστρέφει ή ορίζει την ένταση ήχου σε ποσοστά. |
| [getTrimFromStart()](#getTrimFromStart--) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. |
| [getCaptionTracks()](#getCaptionTracks--) | Αποκτά τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το audio frame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Επιστρέφει ή ορίζει έναν δείκτη αρχικού κομματιού. Ανάγνωση/εγγραφή  int .

**Επιστρέφει:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Επιστρέ φει ή ορίζει έναν δείκτη αρχικού κομματιού. Ανάγνωση/εγγραφή  int .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Επιστρέ φει ή ορίζει χρόνο έναρξης κομματιού. Ανάγνωση/εγγραφή  int .

**Επιστρέ φει:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Επιστρέ φει ή ορίζει χρόνο έναρξης κομματιού. Ανάγνωση/εγγραφή  int .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Επιστρέ φει ή ορίζει έναν τελικό δείκτη κομματιού. Ανάγνωση/εγγραφή  int .

**Επιστρέ φει:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Επιστρέ φει ή ορίζει έναν τελικό δείκτη κομματιού. Ανάγνωση/εγγραφή  int .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Επιστρέ φει ή ορίζει χρόνο λήξης κομματιού. Ανάγνωση/εγγραφή  int .

**Επιστρέ φει:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Επιστρέ φει ή ορίζει χρόνο λήξης κομματιού. Ανάγνωση/εγγραφή  int .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Επιστρέ φει ή ορίζει την ένταση ήχου. Ανάγνωση/εγγραφή [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Επιστρέ φει:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Επιστρέ φει ή ορίζει την ένταση ήχου. Ανάγνωση/εγγραφή [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Επιστρέ φει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. Ανάγνωση/εγγραφή [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Επιστρέ φει:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Επιστρέ φει ή ορίζει τη λειτουργία αναπαραγωγής ήχου. Ανάγνωση/εγγραφή [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Καθορίζει αν ένα AudioFrame είναι κρυφό. Ανάγνωση/εγγραφή  boolean .

**Επιστρέ φει:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Καθορίζει αν ένα AudioFrame είναι κρυφό. Ανάγνωση/εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Καθορίζει αν ένας ήχος επαναλαμβάνεται. Ανάγνωση/εγγραφή  boolean .

**Επιστρέ φει:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Καθορίζει αν ένας ήχος επαναλαμβάνεται. Ανάγνωση/εγγραφή  boolean .

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Καθορίζει αν ο ήχος παίζει διαμέσου των διαφανειών. Ανάγνωση/εγγραφή  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορίζει τον ήχο να επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Επιστρέ φει:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

Καθορίζει αν ο ήχος παίζει διαμέσου των διαφανειών. Ανάγνωση/εγγραφή  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορίζει τον ήχο να επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή
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

Καθορίζει αν ο ήχος επαναξιουράζεται αυτόματα στην αρχή μετά την αναπαραγωγή. Ανάγνωση/εγγραφή  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορίζει τον ήχο να επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Επιστρέ φει:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

Καθορίζει αν ο ήχος επαναξιουράζεται αυτόματα στην αρχή μετά την αναπαραγωγή. Ανάγνωση/εγγραφή  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Προσθήκη Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Ορίζει τον ήχο να παίζει σε όλες τις διαφάνειες
>       audioFrame.setPlayAcrossSlides(true);
>       // Ορίζει τον ήχο να επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή
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

Καθορίζει αν ένας ήχος είναι ενσωματωμένος σε μια παρουσίαση. Μόνο για ανάγνωση  boolean .

**Επιστρέ φει:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Επιστρέ φει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame. Ανάγνωση/εγγραφή String.

**Επιστρέ φει:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Επιστρέ φει ή ορίζει το όνομα ενός αρχείου ήχου που είναι συνδεδεμένο με ένα AudioFrame. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Επιστρέ φει ή ορίζει ενσωματωμένο αντικείμενο ήχου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Επιστρέ φει:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Επιστρέ φει ή ορίζει ενσωματωμένο αντικείμενο ήχου. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Καθορίζει τη διάρκεια χρόνου για την αρχική εναφίπλωση του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τη διάρκεια της αρχικής εναφίπλωσης σε 200ms
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέ φει:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

Καθορίζει τη διάρκεια χρόνου για την αρχική εναφίπλωση του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τη διάρκεια της αρχικής εναφίπλωσης για 200ms
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

Καθορίζει τη διάρκεια χρόνου για την τελική ξεθώριασμα του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

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

**Επιστρέ φει:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

Καθορίζει τη διάρκεια χρόνου για την τελική ξεθώριασμα του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

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

Επιστρέ φει ή ορίζει την ένταση ήχου σε ποσοστά. Ανάγνωση/εγγραφή float.

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

**Επιστρέ φει:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Επιστρέ φει ή ορίζει την ένταση ήχου σε ποσοστά. Ανάγνωση/εγγραφή float.

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

Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τον χρόνο έναρξης περικοπής 1.5 δευτερόλεπτα
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέ φει:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τον χρόνο έναρξης περικοπής 1.5 δευτερόλεπτα
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

Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τον χρόνο λήξης περικοπής 2 δευτερόλεπτα
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέ φει:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση/εγγραφή float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Ορίζει τον χρόνο λήξης περικοπής 2 δευτερόλεπτα
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

Αποκτά τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το audio frame. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) που περιέχει όλα τα κομμάτια υπότιτλων.

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
>              // Αποθηκεύει τα δυαδικά δεδομένα του κομματιού υπότιτλου ως αρχείο .vtt
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


**Επιστρέ φει:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)