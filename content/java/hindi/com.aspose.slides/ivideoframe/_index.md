---
title: IVideoFrame
second_title: जावा के लिए Aspose.Slides API संदर्भ
description: स्लाइड पर एक वीडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ivideoframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

एक स्लाइड पर वीडियो क्लिप को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | निर्धारित करता है कि क्या वीडियो स्वचालित रूप से पुनः शुरू किया जाता है जैसे ही फ़िल्म समाप्त हो जाती है। |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | निर्धारित करता है कि क्या वीडियो स्वचालित रूप से पुनः शुरू किया जाता है जैसे ही फ़िल्म समाप्त हो जाती है। |
| [getPlayLoopMode()](#getPlayLoopMode--) | निर्धारित करता है कि क्या वीडियो लूप किया गया है। |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | निर्धारित करता है कि क्या वीडियो लूप किया गया है। |
| [getHideAtShowing()](#getHideAtShowing--) | निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। |
| [getVolume()](#getVolume--) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है। |
| [setVolume(int value)](#setVolume-int-) | ऑडियो वॉल्यूम को लौटाता है या सेट करता है। |
| [getPlayMode()](#getPlayMode--) | वीडियो प्ले मोड को लौटाता है या सेट करता है। |
| [setPlayMode(int value)](#setPlayMode-int-) | वीडियो प्ले मोड को लौटाता है या सेट करता है। |
| [getFullScreenMode()](#getFullScreenMode--) | निर्धारित करता है कि क्या वीडियो फुल-स्क्रीन मोड में दिखाया गया है। |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | निर्धारित करता है कि क्या वीडियो फुल-स्क्रीन मोड में दिखाया गया है। |
| [getLinkPathLong()](#getLinkPathLong--) | VideoFrame से जुड़े वीडियो फ़ाइल का नाम लौटाता है या सेट करता है। |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | VideoFrame से जुड़े वीडियो फ़ाइल का नाम लौटाता है या सेट करता है। |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | एम्बेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | एम्बेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है। |
| [getTrimFromStart()](#getTrimFromStart--) | शुरुआत ट्रिम [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | शुरुआत ट्रिम [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | अंत ट्रिम [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | अंत ट्रिम [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। |
### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

निर्धारित करता है कि क्या वीडियो स्वचालित रूप से पुनः शुरू किया जाता है जैसे ही फ़िल्म समाप्त हो जाती है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

निर्धारित करता है कि क्या वीडियो स्वचालित रूप से पुनः शुरू किया जाता है जैसे ही फ़िल्म समाप्त हो जाती है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

निर्धारित करता है कि क्या वीडियो लूप किया गया है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

निर्धारित करता है कि क्या वीडियो लूप किया गया है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

निर्धारित करता है कि क्या VideoFrame छिपा हुआ है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

ऑडियो वॉल्यूम को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [AudioVolumeMode](../../com.aspose.slides/audiovolumemode)।

**वापसी:**
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
### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

वीडियो प्ले मोड को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset)।

**वापसी:**
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

निर्धारित करता है कि क्या वीडियो फुल-स्क्रीन मोड में दिखाया गया है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

निर्धारित करता है कि क्या वीडियो फुल-स्क्रीन मोड में दिखाया गया है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

VideoFrame से जुड़े वीडियो फ़ाइल का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**वापसी:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

VideoFrame से जुड़े वीडियो फ़ाइल का नाम लौटाता है या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

एम्बेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IVideo](../../com.aspose.slides/ivideo)।

**वापसी:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

एम्बेडेड वीडियो ऑब्जेक्ट को लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [IVideo](../../com.aspose.slides/ivideo)।

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
>      //ट्रिमिंग शुरू समय 1 सेकंड सेट करें
>      videoFrame.setTrimFromStart(1000f);
>      //ट्रिमिंग समाप्त समय 2 सेकंड सेट करें
>      videoFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
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
>      //कटिंग शुरू समय 1सेकंड सेट करें
>      videoFrame.setTrimFromStart(1000f);
>      //कटिंग समाप्त समय 2सेकंड सेट करें
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

**वापसी:**
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

ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह गुण केवल पढ़ने योग्य है और सभी कैप्शन ट्रैक्स को शामिल करने वाला [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) लौटाता है।

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
>              //कैप्शन बाइनरी डेटा को निकालता है और उसे फ़ाइल में सहेजता है
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)