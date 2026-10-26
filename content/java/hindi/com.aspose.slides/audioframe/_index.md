---
title: AudioFrame
second_title: Aspose.Slides के लिए Java API संदर्भ
description: स्लाइड पर एक ऑडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/audioframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**All Implemented Interfaces:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

स्लाइड पर एक ऑडियो क्लिप का प्रतिनिधित्व करता है।

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // AudioFrame आकार प्राप्त करता है
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // प्ले मोड को क्लिक पर चलाने के लिए सेट करता है
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // वॉल्यूम को Low पर सेट करता है
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // ऑडियो को स्लाइड्स के बीच चलाने के लिए सेट करता है
>      audioFrame.setPlayAcrossSlides(true);
>      // ऑडियो के लिए लूप को अक्षम करता है
>      audioFrame.setPlayLoopMode(false);
>      // स्लाइड शो के दौरान AudioFrame को छिपाता है
>      audioFrame.setHideAtShowing(true);
>      // चलाने के बाद ऑडियो को शुरुआत में रीवाइंड करता है
>      audioFrame.setRewindAudio(true);
>      // PowerPoint फ़ाइल को डिस्क पर सहेजता है
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| Method | Description |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | स्टार्ट ट्रैक इंडेक्स को प्राप्त करता है या सेट करता है। |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | स्टार्ट ट्रैक इंडेक्स को प्राप्त करता है या सेट करता है। |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | स्टार्ट ट्रैक समय को प्राप्त करता है या सेट करता है। |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | स्टार्ट ट्रैक समय को प्राप्त करता है या सेट करता है। |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | आखिरी ट्रैक इंडेक्स को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int । |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | आखिरी ट्रैक इंडेक्स को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int । |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | आखिरी ट्रैक समय को प्राप्त करता है या सेट करता है। |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | आखिरी ट्रैक समय को प्राप्त करता है या सेट करता है। |
| [getVolume()](#getVolume--) | ऑडियो वॉल्यूम को प्राप्त करता है या सेट करता है। |
| [setVolume(int value)](#setVolume-int-) | ऑडियो वॉल्यूम को प्राप्त करता है या सेट करता है। |
| [getPlayMode()](#getPlayMode--) | ऑडियो प्ले मोड को प्राप्त करता है या सेट करता है। |
| [setPlayMode(int value)](#setPlayMode-int-) | ऑडियो प्ले मोड को प्राप्त करता है या सेट करता है। |
| [getHideAtShowing()](#getHideAtShowing--) | निर्धारित करता है कि AudioFrame छिपा हुआ है या नहीं। |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | निर्धारित करता है कि AudioFrame छिपा हुआ है या नहीं। |
| [getPlayLoopMode()](#getPlayLoopMode--) | निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | निर्धारित करता है कि ऑडियो स्लाइड्स के बीच चल रहा है या नहीं। |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | निर्धारित करता है कि ऑडियो स्लाइड्स के बीच चल रहा है या नहीं। |
| [getRewindAudio()](#getRewindAudio--) | निर्धारित करता है कि ऑडियो प्ले करने के बाद स्वचालित रूप से शुरू में रीवाइंड होता है या नहीं। |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | निर्धारित करता है कि ऑडियो प्ले करने के बाद स्वचालित रूप से शुरू में रीवाइंड होता है या नहीं। |
| [getEmbedded()](#getEmbedded--) | निर्धारित करता है कि ध्वनि प्रस्तुति में एम्बेडेड है या नहीं। |
| [getLinkPathLong()](#getLinkPathLong--) | ऑडियो फ़ाइल का नाम प्राप्त करता है या सेट करता है जो AudioFrame से लिंक्ड है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | ऑडियो फ़ाइल का नाम प्राप्त करता है या सेट करता है जो AudioFrame से लिंक्ड है। |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | एम्बेडेड ऑडियो ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | एम्बेडेड ऑडियो ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [getFadeInDuration()](#getFadeInDuration--) | मीडिया के शुरुआती फ़ेड-इन की समयावधि मिलीसेकंड में निर्दिष्ट करता है। |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | मीडिया के शुरुआती फ़ेड-इन की समयावधि मिलीसेकंड में निर्दिष्ट करता है। |
| [getFadeOutDuration()](#getFadeOutDuration--) | मीडिया के समाप्ति फ़ेड-आउट की समयावधि मिलीसेकंड में निर्दिष्ट करता है। |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | मीडिया के समाप्ति फ़ेड-आउट की समयावधि मिलीसेकंड में निर्दिष्ट करता है। |
| [getVolumeValue()](#getVolumeValue--) | ऑडियो वॉल्यूम को प्रतिशत में प्राप्त करता है या सेट करता है। |
| [setVolumeValue(float value)](#setVolumeValue-float-) | ऑडियो वॉल्यूम को प्रतिशत में प्राप्त करता है या सेट करता है। |
| [getTrimFromStart()](#getTrimFromStart--) | मीडिया के प्लेबैक के दौरान शुरुआत से हटाया जाने वाला समयावधी मिलीसेकंड में निर्दिष्ट करता है। |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | मीडिया के प्लेबैक के दौरान शुरुआत से हटाया जाने वाला समयावधी मिलीसेकंड में निर्दिष्ट करता है। |
| [getTrimFromEnd()](#getTrimFromEnd--) | मीडिया के प्लेबैक के दौरान अंत से हटाया जाने वाला समयावधी मिलीसेकंड में निर्दिष्ट करता है। |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | मीडिया के प्लेबैक के दौरान अंत से हटाया जाने वाला समयावधी मिलीसेकंड में निर्दिष्ट करता है। |
| [getCaptionTracks()](#getCaptionTracks--) | ऑडियो फ्रेम से संबंधित क्लोज़्ड कैप्शन का संग्रह प्राप्त करता है। |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

स्टार्ट ट्रैक इंडेक्स को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int ।

**रिटर्न:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

स्टार्ट ट्रैक इंडेक्स को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

स्टार्ट ट्रैक समय को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int ।

**रिटर्न:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

स्टार्ट ट्रैक समय को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

आखिरी ट्रैक इंडेक्स को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int ।

**रिटर्न:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

आखिरी ट्रैक इंडेक्स को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

आखिरी ट्रैक समय को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int ।

**रिटर्न:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

आखिरी ट्रैक समय को प्राप्त करता है या सेट करता है। पढ़ें/लिखें  int ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

ऑडियो वॉल्यूम को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)।

**रिटर्न:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

ऑडियो वॉल्यूम को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

ऑडियो प्ले मोड को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)।

**रिटर्न:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

ऑडियो प्ले मोड को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

निर्धारित करता है कि AudioFrame छिपा हुआ है या नहीं। पढ़ें/लिखें  boolean ।

**रिटर्न:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

निर्धारित करता है कि AudioFrame छिपा हुआ है या नहीं। पढ़ें/लिखें  boolean ।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। पढ़ें/लिखें  boolean ।

**रिटर्न:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। पढ़ें/लिखें  boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

निर्धारित करता है कि ऑडियो स्लाइड्स के बीच चल रहा है या नहीं। पढ़ें/लिखें  boolean .

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइड्स के बीच चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // प्ले करने के बाद ऑडियो को स्वचालित रूप से शुरुआत में रीवाइंड करने के लिए सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**रिटर्न:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public final void setPlayAcrossSlides(boolean value)
```

निर्धारित करता है कि ऑडियो स्लाइड्स के बीच चल रहा है या नहीं। पढ़ें/लिखें  boolean .

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइड्स के बीच चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // प्ले करने के बाद ऑडियो को स्वचालित रूप से शुरुआत में रीवाइंड करने के लिए सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

निर्धारित करता है कि ऑडियो प्ले करने के बाद स्वचालित रूप से शुरू में रीवाइंड होता है या नहीं। पढ़ें/लिखें  boolean .

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइड्स के बीच चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // प्ले करने के बाद ऑडियो को स्वचालित रूप से शुरुआत में रीवाइंड करने के लिए सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**रिटर्न:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public final void setRewindAudio(boolean value)
```

निर्धारित करता है कि ऑडियो प्ले करने के बाद स्वचालित रूप से शुरू में रीवाइंड होता है या नहीं। पढ़ें/लिखें  boolean .

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइड्स के बीच चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // प्ले करने के बाद ऑडियो को स्वचालित रूप से शुरुआत में रीवाइंड करने के लिए सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

निर्धारित करता है कि ध्वनि प्रस्तुति में एम्बेडेड है या नहीं। केवल-पढ़ने योग्य  boolean ।

**रिटर्न:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

ऑडियो फ़ाइल का नाम प्राप्त करता है या सेट करता है जो AudioFrame से लिंक्ड है। पढ़ें/लिखें String।

**रिटर्न:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

ऑडियो फ़ाइल का नाम प्राप्त करता है या सेट करता है जो AudioFrame से लिंक्ड है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

एम्बेडेड ऑडियो ऑब्जेक्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio)।

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

एम्बेडेड ऑडियो ऑब्जेक्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

मीडिया के शुरुआती फ़ेड-इन की समयावधि मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float।

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // प्रारंभिक फ़ेड की अवधि 200ms के लिए सेट करें
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

मीडिया के शुरुआती फ़ेड-इन की समयावधि मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float।

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // प्रारंभिक फ़ेड की अवधि 200ms के लिए सेट करें
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

मीडिया के समाप्ति फ़ेड-आउट की समयावधि मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float।

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // समाप्ति फ़ेड की अवधि 500ms के लिए सेट करें
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public final void setFadeOutDuration(float value)
```

मीडिया के समाप्ति फ़ेड-आउट की समयावधि मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float।

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // समाप्ति फ़ेड की अवधि 500ms के लिए सेट करें
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

ऑडियो वॉल्यूम को प्रतिशत में प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 85% के लिए ऑडियो वॉल्यूम सेट करें
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

ऑडियो वॉल्यूम को प्रतिशत में प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // 85% के लिए ऑडियो वॉल्यूम सेट करें
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

मीडिया के प्लेबैक के दौरान शुरुआत से हटाया जाने वाला समयावधी मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float।

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // शुरू में ट्रिमिंग समय 1.5 सेकंड सेट करें
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

मीडिया के प्लेबैक के दौरान शुरुआत से हटाया जाने वाला समयावधी मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float।

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // शुरू में ट्रिमिंग समय 1.5 सेकंड सेट करें
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

मीडिया के प्लेबैक के दौरान अंत से हटाया जाने वाला समयावधी मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float।

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // अंत ट्रिमिंग समय 2 सेकंड सेट करें
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

मीडिया के प्लेबैक के दौरान अंत से हटाया जाने वाला समयावधी मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float।

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // अंत ट्रिमिंग समय 2 सेकंड सेट करें
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

ऑडियो फ्रेम से संबंधित क्लोज़्ड कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने योग्य है और एक [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) लौटाती है जिसमें सभी कैप्शन ट्रैक शामिल हैं।

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
>              // कैप्शन ट्रैक के बाइनरी डेटा को .vtt फ़ाइल के रूप में सहेजें
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


**रिटर्न:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)