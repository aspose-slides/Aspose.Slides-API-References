---
title: IVideoFrame
second_title: Aspose.Slides Android के लिए जावा API रेफ़रेंस के माध्यम से
description: स्लाइड पर एक वीडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ivideoframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

एक स्लाइड पर वीडियो क्लिप का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | निर्धारित करता है कि क्या वीडियो फ़िल्म समाप्त होते ही स्वचालित रूप से शुरू से पुनः चलाया जाता है। |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | निर्धारित करता है कि क्या वीडियो फ़िल्म समाप्त होते ही स्वचालित रूप से शुरू से पुनः चलाया जाता है। |
| [getPlayLoopMode()](#getPlayLoopMode--) | निर्धारित करता है कि क्या वीडियो लूप किया गया है। |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | निर्धारित करता है कि क्या वीडियो लूप किया गया है। |
| [getHideAtShowing()](#getHideAtShowing--) | निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। |
| [getVolume()](#getVolume--) | ऑडियो वॉल्यूम को प्राप्त करता है या सेट करता है। |
| [setVolume(int value)](#setVolume-int-) | ऑडियो वॉल्यूम को प्राप्त करता है या सेट करता है। |
| [getPlayMode()](#getPlayMode--) | वीडियो प्ले मोड को प्राप्त करता है या सेट करता है। |
| [setPlayMode(int value)](#setPlayMode-int-) | वीडियो प्ले मोड को प्राप्त करता है या सेट करता है। |
| [getFullScreenMode()](#getFullScreenMode--) | निर्धारित करता है कि क्या वीडियो पूर्ण-स्क्रीन मोड में दिखाया जाता है। |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | निर्धारित करता है कि क्या वीडियो पूर्ण-स्क्रीन मोड में दिखाया जाता है। |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame से जुड़ी वीडियो फ़ाइल का नाम प्राप्त करता है या सेट करता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame से जुड़ी वीडियो फ़ाइल का नाम प्राप्त करता है या सेट करता है। |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | एंबेडेड वीडियो ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | एंबेडेड वीडियो ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [getTrimFromStart()](#getTrimFromStart--) | प्रारंभ ट्रिम [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | प्रारंभ ट्रिम [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | समाप्ति ट्रिम [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | समाप्ति ट्रिम [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

निर्धारित करता है कि क्या वीडियो फ़िल्म समाप्त होते ही स्वचालित रूप से शुरू से पुनः चलाया जाता है। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

निर्धारित करता है कि क्या वीडियो फ़िल्म समाप्त होते ही स्वचालित रूप से शुरू से पुनः चलाया जाता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

निर्धारित करता है कि क्या वीडियो लूप किया गया है। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

निर्धारित करता है कि क्या वीडियो लूप किया गया है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

ऑडियो वॉल्यूम को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)।

**रिटर्न:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

ऑडियो वॉल्यूम को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

वीडियो प्ले मोड को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)।

**रिटर्न:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

वीडियो प्ले मोड को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

निर्धारित करता है कि क्या वीडियो पूर्ण-स्क्रीन मोड में दिखाया जाता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

निर्धारित करता है कि क्या वीडियो पूर्ण-स्क्रीन मोड में दिखाया जाता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

VideoFrame से जुड़ी वीडियो फ़ाइल का नाम प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

**रिटर्न:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

VideoFrame से जुड़ी वीडियो फ़ाइल का नाम प्राप्त करता है या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

एंबेडेड वीडियो ऑब्जेक्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IVideo](../../com.aspose.slides/ivideo)।

**रिटर्न:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

एंबेडेड वीडियो ऑब्जेक्ट को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IVideo](../../com.aspose.slides/ivideo)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

प्रारंभ ट्रिम [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ट्रिमिंग प्रारंभ समय 1 सेकंड सेट करें
>      videoFrame.setTrimFromStart(1000f);
>      //ट्रिमिंग समाप्ति समय 2 सेकंड सेट करें
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

प्रारंभ ट्रिम [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(videoData);
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ट्रिमिंग प्रारंभ समय 1 सेकंड सेट करें
>      videoFrame.setTrimFromStart(1000f);
>      //ट्रिमिंग समाप्ति समय 2 सेकंड सेट करें
>      videoFrame.setTrimFromEnd(2000f);
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
public abstract float getTrimFromEnd()
```

समाप्ति ट्रिम [ms]

**रिटर्न:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

समाप्ति ट्रिम [ms]

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने योग्य है और सभी कैप्शन ट्रैक को सम्मिलित करने वाला एक [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) लौटाती है।

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
>              // कैप्शन का बाइनरी डेटा निकालता है और उसे फ़ाइल में सहेजता है
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)