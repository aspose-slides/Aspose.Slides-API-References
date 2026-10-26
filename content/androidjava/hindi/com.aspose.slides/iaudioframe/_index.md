---
title: IAudioFrame
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक स्लाइड पर ऑडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iaudioframe/
---
**सभी लागू इंटरफ़ेस:** 
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

एक स्लाइड पर ऑडियो क्लिप का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | स्टार्ट ट्रैक इंडेक्स को लौटाता है या सेट करता है। |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | स्टार्ट ट्रैक इंडेक्स को लौटाता है या सेट करता है। |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | स्टार्ट ट्रैक समय को लौटाता है या सेट करता है। |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | स्टार्ट ट्रैक समय को लौटाता है या सेट करता है। |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | अंतिम ट्रैक इंडेक्स को लौटाता है या सेट करता है पढ़ें/लिखें int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | अंतिम ट्रैक इंडेक्स को लौटाता है या सेट करता है पढ़ें/लिखें int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | अंतिम ट्रैक समय को लौटाता है या सेट करता है। |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | अंतिम ट्रैक समय को लौटाता है या सेट करता है। |
| [getVolume()](#getVolume--) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है। |
| [setVolume(int value)](#setVolume-int-) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है। |
| [getPlayMode()](#getPlayMode--) | ऑडियो प्ले मोड को लौटाता है या सेट करता है। |
| [setPlayMode(int value)](#setPlayMode-int-) | ऑडियो प्ले मोड को लौटाता है या सेट करता है। |
| [getHideAtShowing()](#getHideAtShowing--) | निर्धारित करता है कि AudioFrame छिपा है या नहीं। |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | निर्धारित करता है कि AudioFrame छिपा है या नहीं। |
| [getPlayLoopMode()](#getPlayLoopMode--) | निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | निर्धारित करता है कि ऑडियो स्लाइडों के across बज रहा है या नहीं। |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | निर्धारित करता है कि ऑडियो स्लाइडों के across बज रहा है या नहीं। |
| [getRewindAudio()](#getRewindAudio--) | निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू बिंदु पर रीवाइंड होता है या नहीं। |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू बिंदु पर रीवाइंड होता है या नहीं। |
| [getEmbedded()](#getEmbedded--) | निर्धारित करता है कि ध्वनि प्रस्तुति में एम्बेड की गई है या नहीं। |
| [getLinkPathLong()](#getLinkPathLong--) | ऑडियो फ़ाइल का नाम लौटाता है या सेट करता है जो AudioFrame से लिंक्ड है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | ऑडियो फ़ाइल का नाम लौटाता है या सेट करता है जो AudioFrame से लिंक्ड है। |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | एंबेडेड ऑडियो ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | एंबेडेड ऑडियो ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getFadeInDuration()](#getFadeInDuration--) | मीडिया की प्रारंभिक फेड-इन अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | मीडिया की प्रारंभिक फेड-इन अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [getFadeOutDuration()](#getFadeOutDuration--) | मीडिया के अंत फेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | मीडिया के अंत फेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [getVolumeValue()](#getVolumeValue--) | ऑडियो वॉल्यूम को प्रतिशत में लौटाता है या सेट करता है। |
| [setVolumeValue(float value)](#setVolumeValue-float-) | ऑडियो वॉल्यूम को प्रतिशत में लौटाता है या सेट करता है। |
| [getTrimFromStart()](#getTrimFromStart--) | प्लेबैक के दौरान मीडिया की शुरुआत से हटाने के लिए समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | प्लेबैक के दौरान मीडिया की शुरुआत से हटाने के लिए समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [getTrimFromEnd()](#getTrimFromEnd--) | प्लेबैक के दौरान मीडिया के अंत से हटाने के लिए समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | प्लेबैक के दौरान मीडिया के अंत से हटाने के लिए समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [getCaptionTracks()](#getCaptionTracks--) | ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

स्टार्ट ट्रैक इंडेक्स को लौटाता है या सेट करता है। पढ़ें/लिखें int.

**रिटर्न:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

स्टार्ट ट्रैक इंडेक्स को लौटाता है या सेट करता है। पढ़ें/लिखें int.

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

स्टार्ट ट्रैक समय को लौटाता है या सेट करता है। पढ़ें/लिखें int.

**रिटर्न:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

स्टार्ट ट्रैक समय को लौटाता है या सेट करता है। पढ़ें/लिखें int.

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

अंतिम ट्रैक इंडेक्स को लौटाता है या सेट करता है पढ़ें/लिखें int.

**रिटर्न:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

अंतिम ट्रैक इंडेक्स को लौटाता है या सेट करता है पढ़ें/लिखें int.

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

अंतिम ट्रैक समय को लौटाता है या सेट करता है पढ़ें/लिखें int.

**रिटर्न:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

अंतिम ट्रैक समय को लौटाता है या सेट करता है पढ़ें/लिखें int.

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

ऑडियो वॉल्यूम को लौटाता है या सेट करता है पढ़ें/लिखें [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**रिटर्न:**
int

### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

ऑडियो वॉल्यूम को लौटाता है या सेट करता है पढ़ें/लिखें [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

ऑडियो प्ले मोड को लौटाता है या सेट करता है पढ़ें/लिखें [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**रिटर्न:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

ऑडियो प्ले मोड को लौटाता है या सेट करता है पढ़ें/लिखें [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

निर्धारित करता है कि AudioFrame छिपा है या नहीं पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

निर्धारित करता है कि AudioFrame छिपा है या नहीं पढ़ें/लिखें boolean.

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं पढ़ें/लिखें boolean.

**रिटर्न:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं पढ़ें/लिखें boolean.

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

निर्धारित करता है कि ऑडियो स्लाइडों के across बज रहा है या नहीं पढ़ें/लिखें boolean.

--------------------

> ``` 
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइडों के पार चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // ऑडियो को प्ले होने के बाद स्वचालित रूप से प्रारंभ पर रीवाइंड करने के लिए सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> 
```

**रिटर्न:**
boolean

### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

निर्धारित करता है कि ऑडियो स्लाइडों के across बज रहा है या नहीं पढ़ें/लिखें boolean.

--------------------

> ``` 
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइडों के पार चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // ऑडियो को प्ले होने के बाद स्वचालित रूप से शुरू पर रीवाइंड करने के लिए सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> 
```

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू बिंदु पर रीवाइंड होता है या नहीं पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइडों के पार चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // ऑडियो को प्ले होने के बाद स्वचालित रूप से प्रारंभ पर रीवाइंड करने के लिए सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> 
```

**रिटर्न:**
boolean

### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू बिंदु पर रीवाइंड होता है या नहीं पढ़ें/लिखें boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइडों के पार चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // ऑडियो को प्ले होने के बाद स्वचालित रूप से प्रारंभ पर रीवाइंड करने के लिए सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> 
```

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

निर्धारित करता है कि ध्वनि प्रस्तुति में एम्बेड की गई है या नहीं केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

ऑडियो फ़ाइल का नाम लौटाता है या सेट करता है जो AudioFrame से लिंक्ड है पढ़ें/लिखें String.

**रिटर्न:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

ऑडियो फ़ाइल का नाम लौटाता है या सेट करता है जो AudioFrame से लिंक्ड है पढ़ें/लिखें String.

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

एम्बेडेड ऑडियो ऑब्जेक्ट को लौटाता है या सेट करता है पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio).

**रिटर्न:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

एम्बेडेड ऑडियो ऑब्जेक्ट को लौटाता है या सेट करता है पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio).

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

मीडिया की प्रारंभिक फेड-इन अवधि को मिलीसेकंड में निर्दिष्ट करता है पढ़ें/लिखें float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // शुरुआती फेड की अवधि 200ms के लिए सेट करें
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> 
```

**रिटर्न:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

मीडिया की प्रारंभिक फेड-इन अवधि को मिलीसेकंड में निर्दिष्ट करता है पढ़ें/लिखें float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // शुरुआती फेड की अवधि 200ms के लिए सेट करें
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> 
```

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

मीडिया के अंत फेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है पढ़ें/लिखें float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // समाप्ति फेड की अवधि 500ms के लिए सेट करें
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> 
```

**रिटर्न:**
float

### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

मीडिया के अंत फेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है पढ़ें/लिखें float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // अंतिम फेड की अवधि 500ms के लिए सेट करें
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> 
```

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

ऑडियो वॉल्यूम को प्रतिशत में लौटाता है या सेट करता है पढ़ें/लिखें float.

--------------------

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
> 
```

**रिटर्न:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

ऑडियो वॉल्यूम को प्रतिशत में लौटाता है या सेट करता है पढ़ें/लिखें float.

--------------------

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
> 
```

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

प्लेबैक के दौरान मीडिया की शुरुआत से हटाने के लिए समय अवधि को मिलीसेकंड में निर्दिष्ट करता है पढ़ें/लिखें float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // शुरू ट्रिमिंग समय 1.5 सेकंड सेट करें
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> 
```

**रिटर्न:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

प्लेबैक के दौरान मीडिया की शुरुआत से हटाने के लिए समय अवधि को मिलीसेकंड में निर्दिष्ट करता है पढ़ें/लिखें float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // शुरू ट्रिमिंग समय 1.5 सेकंड सेट करें
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> 
```

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

प्लेबैक के दौरान मीडिया के अंत से हटाने के लिए समय अवधि को मिलीसेकंड में निर्दिष्ट करता है पढ़ें/लिखें float.

--------------------

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
> 
```

**रिटर्न:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

प्लेबैक के दौरान मीडिया के अंत से हटाने के लिए समय अवधि को मिलीसेकंड में निर्दिष्ट करता है पढ़ें/लिखें float.

--------------------

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
> 
```

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने योग्य है और एक [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) लौटाता है जिसमें सभी कैप्शन ट्रैक्स होते हैं।

--------------------

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
>             // कैप्शन ट्रैक का बाइनरी डेटा .vtt फ़ाइल के रूप में सहेजें
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
> 
```

**रिटर्न:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)