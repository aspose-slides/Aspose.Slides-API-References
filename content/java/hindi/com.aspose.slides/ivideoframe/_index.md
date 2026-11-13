---
title: IVideoFrame
second_title: Aspose.Slides के लिए Java API संदर्भ
description: स्लाइड पर एक वीडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ivideoframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

स्लाइड पर एक वीडियो क्लिप का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | निर्धारित करता है कि क्या वीडियो फ़िल्म समाप्त होने के तुरंत बाद स्वचालित रूप से शुरू से रीवाइंड हो जाता है। |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | निर्धारित करता है कि क्या वीडियो फ़िल्म समाप्त होने के तुरंत बाद स्वचालित रूप से शुरू से रीवाइंड हो जाता है। |
| [getPlayLoopMode()](#getPlayLoopMode--) | निर्धारित करता है कि क्या वीडियो लूप किया गया है। |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | निर्धारित करता है कि क्या वीडियो लूप किया गया है। |
| [getHideAtShowing()](#getHideAtShowing--) | निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। |
| [getVolume()](#getVolume--) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है। |
| [setVolume(int value)](#setVolume-int-) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है। |
| [getVolumeValue()](#getVolumeValue--) | वीडियो वॉल्यूम को प्रतिशत के रूप में सटीक रूप से लौटाता है या सेट करता है। |
| [setVolumeValue(float value)](#setVolumeValue-float-) | वीडियो वॉल्यूम को प्रतिशत के रूप में सटीक रूप से लौटाता है या सेट करता है। |
| [getPlayMode()](#getPlayMode--) | वीडियो प्ले मोड को लौटाता है या सेट करता है। |
| [setPlayMode(int value)](#setPlayMode-int-) | वीडियो प्ले मोड को लौटाता है या सेट करता है। |
| [getFullScreenMode()](#getFullScreenMode--) | निर्धारित करता है कि क्या वीडियो पूर्ण स्क्रीन मोड में दिखाया जाता है। |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | निर्धारित करता है कि क्या वीडियो पूर्ण स्क्रीन मोड में दिखाया जाता है। |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame से जुड़ी वीडियो फ़ाइल का नाम लौटाता है या सेट करता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame से जुड़ी वीडियो फ़ाइल का नाम लौटाता है या सेट करता है। |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | एंबेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | एंबेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getTrimFromStart()](#getTrimFromStart--) | शुरू ट्रिम [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | शुरू ट्रिम [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | अंत ट्रिम [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | अंत ट्रिम [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | ऑडियो फ्रेम से जुड़े क्लोज़्ड कैप्शन के संग्रह को प्राप्त करता है। |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

निर्धारित करता है कि क्या वीडियो फ़िल्म समाप्त होने के तुरंत बाद स्वचालित रूप से शुरू से रीवाइंड हो जाता है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**  
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

निर्धारित करता है कि क्या वीडियो फ़िल्म समाप्त होने के तुरंत बाद स्वचालित रूप से शुरू से रीवाइंड हो जाता है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

निर्धारित करता है कि क्या वीडियो लूप किया गया है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**  
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

निर्धारित करता है कि क्या वीडियो लूप किया गया है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**  
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

ऑडियो वॉल्यूम को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)।

**रिटर्न:**  
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

ऑडियो वॉल्यूम को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

वीडियो वॉल्यूम को प्रतिशत के रूप में सटीक रूप से लौटाता है या सेट करता है। मान 0 से 100 के प्रतिशत के रूप में व्यक्त किया जाता है। इस प्रॉपर्टी का उपयोग अधिक सटीक वॉल्यूम मान पढ़ने या सेट करने के लिए किया जाता है, जो पूर्वनिर्धारित स्तरों से बेहतर है, जिनकी उपलब्धता Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) प्रॉपर्टी में है। पढ़ने/लिखने योग्य float।

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // वर्तमान सटीक वॉल्यूम पढ़ें और इसे 75.5 प्रतिशत पर सेट करें।
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**  
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

वीडियो वॉल्यूम को प्रतिशत के रूप में सटीक रूप से लौटाता है या सेट करता है। मान 0 से 100 के प्रतिशत के रूप में व्यक्त किया जाता है। इस प्रॉपर्टी का उपयोग अधिक सटीक वॉल्यूम मान पढ़ने या सेट करने के लिए किया जाता है, जो पूर्वनिर्धारित स्तरों से बेहतर है, जिनकी उपलब्धता Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)) प्रॉपर्टी में है। पढ़ने/लिखने योग्य float।

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // वर्तमान सटीक वॉल्यूम पढ़ें और इसे 75.5 प्रतिशत पर सेट करें।
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

वीडियो प्ले मोड को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)।

**रिटर्न:**  
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

वीडियो प्ले मोड को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

निर्धारित करता है कि क्या वीडियो पूर्ण स्क्रीन मोड में दिखाया जाता है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**  
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

निर्धारित करता है कि क्या वीडियो पूर्ण स्क्रीन मोड में दिखाया जाता है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

VideoFrame से जुड़ी वीडियो फ़ाइल का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**  
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

VideoFrame से जुड़ी वीडियो फ़ाइल का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

एंबेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IVideo](../../com.aspose.slides/ivideo)।

**रिटर्न:**  
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

एंबेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IVideo](../../com.aspose.slides/ivideo)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |
### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

शुरुआत ट्रिम [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ट्रिमिंग शुरू समय 1सेक सेट करें
>      videoFrame.setTrimFromStart(1000f);
>      //ट्रिमिंग अंत समय 2सेक सेट करें
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

शुरुआत ट्रिम [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //ट्रिमिंग शुरू समय 1सेक सेट करें
>      videoFrame.setTrimFromStart(1000f);
>      //ट्रिमिंग अंत समय 2सेक सेट करें
>      videoFrame.setTrimFromEnd(2000f);
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
public abstract float getTrimFromEnd()
```

अंत ट्रिम [ms]

**रिटर्न:**  
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

अंत ट्रिम [ms]

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

ऑडियो फ्रेम से जुड़े क्लोज़्ड कैप्शन के संग्रह को प्राप्त करता है। यह प्रॉपर्टी केवल पढ़ने योग्य है और सभी कैप्शन ट्रैक्स को शामिल करने वाला [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) लौटाता है।

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
>              // कैप्शन की बाइनरी डेटा को निकालता है और फ़ाइल में सहेजता है
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