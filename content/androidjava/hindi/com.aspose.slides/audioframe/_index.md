---
title: AudioFrame
second_title: Aspose.Slides for Android, Java API संदर्भ के माध्यम से
description: एक स्लाइड पर ऑडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/audioframe/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)  
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

एक स्लाइड पर ऑडियो क्लिप का प्रतिनिधित्व करता है।

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // AudioFrame आकृति प्राप्त करता है
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Play मोड को क्लिक पर चलाने के लिये सेट करता है
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // वॉल्यूम को Low पर सेट करता है
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // ऑडियो को स्लाइडों के पार चलाने के लिये सेट करता है
>      audioFrame.setPlayAcrossSlides(true);
>      // ऑडियो के लूप को अक्षम करता है
>      audioFrame.setPlayLoopMode(false);
>      // स्लाइड शो के दौरान AudioFrame को छुपाता है
>      audioFrame.setHideAtShowing(true);
>      // बजाने के बाद ऑडियो को शुरू में रीवाइंड करता है
>      audioFrame.setRewindAudio(true);
>      // PowerPoint फ़ाइल को डिस्क पर सहेजता है
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | एक प्रारंभ ट्रैक इंडेक्स को लौटाता है या सेट करता है। |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | एक प्रारंभ ट्रैक इंडेक्स को लौटाता है या सेट करता है। |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | एक प्रारंभ ट्रैक समय को लौटाता है या सेट करता है। |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | एक प्रारंभ ट्रैक समय को लौटाता है या सेट करता है। |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | अंतिम ट्रैक इंडेक्स को लौटाता है या सेट करता है। पढ़ें/लिखें  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | अंतिम ट्रैक इंडेक्स को लौटाता है या सेट करता है। पढ़ें/लिखें  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | अंतिम ट्रैक समय को लौटाता है या सेट करता है। |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | अंतिम ट्रैक समय को लौटाता है या सेट करता है। |
| [getVolume()](#getVolume--) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है। |
| [setVolume(int value)](#setVolume-int-) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है। |
| [getPlayMode()](#getPlayMode--) | ऑडियो प्ले मोड को लौटाता है या सेट करता है। |
| [setPlayMode(int value)](#setPlayMode-int-) | ऑडियो प्ले मोड को लौटाता है या सेट करता है। |
| [getHideAtShowing()](#getHideAtShowing--) | यह निर्धारित करता है कि AudioFrame छिपा है या नहीं। |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | यह निर्धारित करता है कि AudioFrame छिपा है या नहीं। |
| [getPlayLoopMode()](#getPlayLoopMode--) | यह निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | यह निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | यह निर्धारित करता है कि ऑडियो स्लाइडों के पार चल रहा है या नहीं। |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | यह निर्धारित करता है कि ऑडियो स्लाइडों के पार चल रहा है या नहीं। |
| [getRewindAudio()](#getRewindAudio--) | यह निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू में रिवाइंड किया जाता है या नहीं। |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | यह निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू में रिवाइंड किया जाता है या नहीं। |
| [getEmbedded()](#getEmbedded--) | यह निर्धारित करता है कि ध्वनि प्रस्तुति में एम्बेड की गई है या नहीं। |
| [getLinkPathLong()](#getLinkPathLong--) | AudioFrame से लिंक किए गए ऑडियो फ़ाइल का नाम लौटाता है या सेट करता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | AudioFrame से लिंक किए गए ऑडियो फ़ाइल का नाम लौटाता है या सेट करता है। |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | एम्बेडेड ऑडियो ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | एम्बेडेड ऑडियो ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getFadeInDuration()](#getFadeInDuration--) | मीडिया के प्रारंभिक फ़ेड-इन की अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | मीडिया के प्रारंभिक फ़ेड-इन की अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [getFadeOutDuration()](#getFadeOutDuration--) | मीडिया के अंत फ़ेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | मीडिया के अंत फ़ेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [getVolumeValue()](#getVolumeValue--) | ऑडियो वॉल्यूम को प्रतिशत में लौटाता है या सेट करता है। |
| [setVolumeValue(float value)](#setVolumeValue-float-) | ऑडियो वॉल्यूम को प्रतिशत में लौटाता है या सेट करता है। |
| [getTrimFromStart()](#getTrimFromStart--) | प्लेबैक के दौरान मीडिया की शुरुआत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | प्लेबैक के दौरान मीडिया की शुरुआत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [getTrimFromEnd()](#getTrimFromEnd--) | प्लेबैक के दौरान मीडिया के अंत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | प्लेबैक के दौरान मीडिया के अंत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। |
| [getCaptionTracks()](#getCaptionTracks--) | ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

एक प्रारंभ ट्रैक इंडेक्स को लौटाता है या सेट करता है। पढ़ें/लिखें  int .

**रिटर्न:**  
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

एक प्रारंभ ट्रैक इंडेक्स को लौटाता है या सेट करता है। पढ़ें/लिखें  int .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

एक प्रारंभ ट्रैक समय को लौटाता है या सेट करता है। पढ़ें/लिखें  int .

**रिटर्न:**  
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

एक प्रारंभ ट्रैक समय को लौटाता है या सेट करता है। पढ़ें/लिखें  int .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

अंतिम ट्रैक इंडेक्स को लौटाता है या सेट करता है। पढ़ें/लिखें  int .

**रिटर्न:**  
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

अंतिम ट्रैक इंडेक्स को लौटाता है या सेट करता है। पढ़ें/लिखें  int .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

अंतिम ट्रैक समय को लौटाता है या सेट करता है। पढ़ें/लिखें  int .

**रिटर्न:**  
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

अंतिम ट्रैक समय को लौटाता है या सेट करता है। पढ़ें/लिखें  int .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

ऑडियो वॉल्यूम को लौटाता है या सेट करता है। पढ़ें/लिखें [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**रिटर्न:**  
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

ऑडियो वॉल्यूम को लौटाता है या सेट करता है। पढ़ें/लिखें [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

ऑडियो प्ले मोड को लौटाता है या सेट करता है। पढ़ें/लिखें [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**रिटर्न:**  
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

ऑडियो प्ले मोड को लौटाता है या सेट करता है। पढ़ें/लिखें [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

यह निर्धारित करता है कि AudioFrame छिपा है या नहीं। पढ़ें/लिखें  boolean .

**रिटर्न:**  
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

यह निर्धारित करता है कि AudioFrame छिपा है या नहीं। पढ़ें/लिखें  boolean .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

यह निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। पढ़ें/लिखें  boolean .

**रिटर्न:**  
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

यह निर्धारित करता है कि ऑडियो लूप किया गया है या नहीं। पढ़ें/लिखें  boolean .

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

यह निर्धारित करता है कि ऑडियो स्लाइडों के पार चल रहा है या नहीं। पढ़ें/लिखें  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइडों के पार चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // ऑडियो को प्ले होने के बाद स्वचालित रूप से शुरू में रीवाइंड करने के लिए सेट करें
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

यह निर्धारित करता है कि ऑडियो स्लाइडों के पार चल रहा है या नहीं। पढ़ें/लिखें  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइडों के पार चलाने के लिये सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // ऑडियो को प्ले होने के बाद स्वचालित रूप से शुरू में रीवाइंड करने के लिये सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public final boolean getRewindAudio()
```

यह निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू में रिवाइंड किया जाता है या नहीं। पढ़ें/लिखें  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइडों के पार चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // ऑडियो को प्ले होने के बाद स्वचालित रूप से शुरू में रीवाइंड करने के लिए सेट करें
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

यह निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू में रिवाइंड किया जाता है या नहीं। पढ़ें/लिखें  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // ऑडियो फ्रेम जोड़ें
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // ऑडियो को स्लाइडों के पार चलाने के लिए सेट करें
>       audioFrame.setPlayAcrossSlides(true);
>       // ऑडियो को प्ले होने के बाद स्वचालित रूप से शुरू में रीवाइंड करने के लिए सेट करें
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public final boolean getEmbedded()
```

यह निर्धारित करता है कि ध्वनि प्रस्तुति में एम्बेड की गई है या नहीं। केवल-पढ़ने योग्य  boolean .

**रिटर्न:**  
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

AudioFrame से लिंक किए गए ऑडियो फ़ाइल का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String.

**रिटर्न:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

AudioFrame से लिंक किए गए ऑडियो फ़ाइल का नाम लौटाता है या सेट करता है। पढ़ें/लिखें String.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

एम्बेडेड ऑडियो ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio).

**रिटर्न:**  
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

एम्बेडेड ऑडियो ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ें/लिखें [IAudio](../../com.aspose.slides/iaudio).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

मीडिया के प्रारंभिक फ़ेड-इन की अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // शुरुआती फ़ेड की अवधि को 200ms के लिए सेट करें
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

मीडिया के प्रारंभिक फ़ेड-इन की अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // शुरुआती फ़ेड की अवधि को 200ms के लिए सेट करें
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public final float getFadeOutDuration()
```

मीडिया के अंत फ़ेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // अंत फ़ेड की अवधि को 500ms के लिए सेट करें
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

मीडिया के अंत फ़ेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // अंत फ़ेड की अवधि को 500ms के लिए सेट करें
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public final float getVolumeValue()
```

ऑडियो वॉल्यूम को प्रतिशत में लौटाता है या सेट करता है। पढ़ें/लिखें float.

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
> ```

**रिटर्न:**  
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

ऑडियो वॉल्यूम को प्रतिशत में लौटाता है या सेट करता है। पढ़ें/लिखें float.

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
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public final float getTrimFromStart()
```

प्लेबैक के दौरान मीडिया की शुरुआत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // प्रारंभ ट्रिमिंग समय 1.5 सेकंड सेट करें
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

प्लेबैक के दौरान मीडिया की शुरुआत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // प्रारंभ ट्रिमिंग समय 1.5 सेकंड सेट करें
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public final float getTrimFromEnd()
```

प्लेबैक के दौरान मीडिया के अंत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // समाप्ति ट्रिमिंग समय 2 सेकंड सेट करें
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

प्लेबैक के दौरान मीडिया के अंत से हटाए जाने वाले समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें/लिखें float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // समाप्ति ट्रिमिंग समय 2 सेकंड सेट करें
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public final ICaptionsCollection getCaptionTracks()
```

ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने योग्य है और सभी कैप्शन ट्रैक वाले एक [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) को लौटाती है।

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