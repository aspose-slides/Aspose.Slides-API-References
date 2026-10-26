---
title: IAudioFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một đoạn âm thanh trên slide.
type: docs
url: /vi/com.aspose.slides/iaudioframe/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IAudioFrame extends IPictureFrame
```

Biểu diễn một đoạn âm thanh trên slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Trả về hoặc đặt chỉ mục track bắt đầu. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Trả về hoặc đặt chỉ mục track bắt đầu. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Trả về hoặc đặt thời gian track bắt đầu. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Trả về hoặc đặt thời gian track bắt đầu. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Trả về hoặc đặt chỉ mục track cuối cùng Đọc/ghi int. |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Trả về hoặc đặt chỉ mục track cuối cùng Đọc/ghi int. |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Trả về hoặc đặt thời gian track cuối cùng. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Trả về hoặc đặt thời gian track cuối cùng. |
| [getVolume()](#getVolume--) | Trả về hoặc đặt âm lượng âm thanh. |
| [setVolume(int value)](#setVolume-int-) | Trả về hoặc đặt âm lượng âm thanh. |
| [getPlayMode()](#getPlayMode--) | Trả về hoặc đặt chế độ phát âm thanh. |
| [setPlayMode(int value)](#setPlayMode-int-) | Trả về hoặc đặt chế độ phát âm thanh. |
| [getHideAtShowing()](#getHideAtShowing--) | Xác định liệu AudioFrame có bị ẩn hay không. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Xác định liệu AudioFrame có bị ẩn hay không. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Xác định liệu âm thanh có được lặp lại hay không. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Xác định liệu âm thanh có được lặp lại hay không. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Xác định liệu âm thanh có phát xuyên suốt các slide hay không. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Xác định liệu âm thanh có phát xuyên suốt các slide hay không. |
| [getRewindAudio()](#getRewindAudio--) | Xác định liệu âm thanh có tự động quay lại đầu sau khi phát hay không. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Xác định liệu âm thanh có tự động quay lại đầu sau khi phát hay không. |
| [getEmbedded()](#getEmbedded--) | Xác định liệu âm thanh có được nhúng vào bản trình chiếu hay không. |
| [getLinkPathLong()](#getLinkPathLong--) | Trả về hoặc đặt tên của tệp âm thanh được liên kết với AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Trả về hoặc đặt tên của tệp âm thanh được liên kết với AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Trả về hoặc đặt đối tượng âm thanh nhúng. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Trả về hoặc đặt đối tượng âm thanh nhúng. |
| [getFadeInDuration()](#getFadeInDuration--) | Xác định khoảng thời gian fade-in ban đầu của media tính bằng mili giây. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Xác định khoảng thời gian fade-in ban đầu của media tính bằng mili giây. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Xác định khoảng thời gian fade-out cuối cùng của media tính bằng mili giây. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Xác định khoảng thời gian fade-out cuối cùng của media tính bằng mili giây. |
| [getVolumeValue()](#getVolumeValue--) | Trả về hoặc đặt âm lượng âm thanh tính bằng phần trăm. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Trả về hoặc đặt âm lượng âm thanh tính bằng phần trăm. |
| [getTrimFromStart()](#getTrimFromStart--) | Xác định khoảng thời gian sẽ bị loại bỏ từ đầu media trong quá trình phát, tính bằng mili giây. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Xác định khoảng thời gian sẽ bị loại bỏ từ đầu media trong quá trình phát, tính bằng mili giây. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Xác định khoảng thời gian sẽ bị loại bỏ từ cuối media trong quá trình phát, tính bằng mili giây. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Xác định khoảng thời gian sẽ bị loại bỏ từ cuối media trong quá trình phát, tính bằng mili giây. |
| [getCaptionTracks()](#getCaptionTracks--) | Lấy bộ sưu tập phụ đề đóng liên quan đến khung âm thanh. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public abstract int getAudioCdStartTrack()
```

Trả về hoặc đặt chỉ mục track bắt đầu. Đọc/ghi int.

**Trả về:**
int
### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public abstract void setAudioCdStartTrack(int value)
```

Trả về hoặc đặt chỉ mục track bắt đầu. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public abstract int getAudioCdStartTrackTime()
```

Trả về hoặc đặt thời gian track bắt đầu. Đọc/ghi int.

**Trả về:**
int
### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public abstract void setAudioCdStartTrackTime(int value)
```

Trả về hoặc đặt thời gian track bắt đầu. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public abstract int getAudioCdEndTrack()
```

Trả về hoặc đặt chỉ mục track cuối cùng Đọc/ghi int.

**Trả về:**
int
### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public abstract void setAudioCdEndTrack(int value)
```

Trả về hoặc đặt chỉ mục track cuối cùng Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public abstract int getAudioCdEndTrackTime()
```

Trả về hoặc đặt thời gian track cuối cùng Đọc/ghi int.

**Trả về:**
int
### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public abstract void setAudioCdEndTrackTime(int value)
```

Trả về hoặc đặt thời gian track cuối cùng Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public abstract int getVolume()
```

Trả về hoặc đặt âm lượng âm thanh. Đọc/ghi [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Trả về:**
int
### setVolume(int value) {#setVolume-int-}
```
public abstract void setVolume(int value)
```

Trả về hoặc đặt âm lượng âm thanh. Đọc/ghi [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Trả về hoặc đặt chế độ phát âm thanh. Đọc/ghi [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Trả về:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Trả về hoặc đặt chế độ phát âm thanh. Đọc/ghi [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Xác định liệu AudioFrame có bị ẩn hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Xác định liệu AudioFrame có bị ẩn hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Xác định liệu âm thanh có được lặp lại hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Xác định liệu âm thanh có được lặp lại hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public abstract boolean getPlayAcrossSlides()
```

Xác định liệu âm thanh có phát xuyên suốt các slide hay không. Đọc/ghi boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Thêm khung âm thanh
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Đặt âm thanh phát xuyên suốt các slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Đặt âm thanh tự động quay lại đầu sau khi phát
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Trả về:**
boolean
### setPlayAcrossSlides(boolean value) {#setPlayAcrossSlides-boolean-}
```
public abstract void setPlayAcrossSlides(boolean value)
```

Xác định liệu âm thanh có phát xuyên suốt các slide hay không. Đọc/ghi boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Thêm Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Đặt Audio phát xuyên suốt các slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Đặt Audio tự động quay lại đầu sau khi phát
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getRewindAudio() {#getRewindAudio--}
```
public abstract boolean getRewindAudio()
```

Xác định liệu âm thanh có tự động quay lại đầu sau khi phát hay không. Đọc/ghi boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Thêm Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Đặt Audio phát xuyên suốt các slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Đặt Audio tự động quay lại đầu sau khi phát
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Trả về:**
boolean
### setRewindAudio(boolean value) {#setRewindAudio-boolean-}
```
public abstract void setRewindAudio(boolean value)
```

Xác định liệu âm thanh có tự động quay lại đầu sau khi phát hay không. Đọc/ghi boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>   try{
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Thêm Audio Frame
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Đặt Audio phát xuyên suốt các slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Đặt Audio tự động quay lại đầu sau khi phát
>       audioFrame.setRewindAudio(true);
>       pres.save("AudioFrame_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEmbedded() {#getEmbedded--}
```
public abstract boolean getEmbedded()
```

Xác định liệu âm thanh có được nhúng vào bản trình chiếu hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Trả về hoặc đặt tên của tệp âm thanh được liên kết với AudioFrame. Đọc/ghi String.

**Trả về:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Trả về hoặc đặt tên của tệp âm thanh được liên kết với AudioFrame. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public abstract IAudio getEmbeddedAudio()
```

Trả về hoặc đặt đối tượng âm thanh nhúng. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio)
### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public abstract void setEmbeddedAudio(IAudio value)
```

Trả về hoặc đặt đối tượng âm thanh nhúng. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public abstract float getFadeInDuration()
```

Xác định khoảng thời gian fade-in ban đầu của media tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời lượng fade-in ban đầu là 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
float
### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public abstract void setFadeInDuration(float value)
```

Xác định khoảng thời gian fade-in ban đầu của media tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời lượng fade-in ban đầu là 200ms
>      audioFrame.setFadeInDuration(200f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getFadeOutDuration() {#getFadeOutDuration--}
```
public abstract float getFadeOutDuration()
```

Xác định khoảng thời gian fade-out cuối cùng của media tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời lượng fade-out cuối cùng là 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
float
### setFadeOutDuration(float value) {#setFadeOutDuration-float-}
```
public abstract void setFadeOutDuration(float value)
```

Xác định khoảng thời gian fade-out cuối cùng của media tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời lượng fade-out cuối cùng là 500ms
>      audioFrame.setFadeOutDuration(500f);
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Trả về hoặc đặt âm lượng âm thanh tính bằng phần trăm. Đọc/ghi float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt âm lượng âm thanh thành 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
float
### setVolumeValue(float value) {#setVolumeValue-float-}
```
public abstract void setVolumeValue(float value)
```

Trả về hoặc đặt âm lượng âm thanh tính bằng phần trăm. Đọc/ghi float.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt âm lượng âm thanh thành 85%
>      audioFrame.setVolumeValue(85f);
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Xác định khoảng thời gian sẽ bị loại bỏ từ đầu media trong quá trình phát, tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời gian cắt đầu 1.5 giây
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
float
### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public abstract void setTrimFromStart(float value)
```

Xác định khoảng thời gian sẽ bị loại bỏ từ đầu media trong quá trình phát, tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời gian cắt đầu 1.5 giây
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTrimFromEnd() {#getTrimFromEnd--}
```
public abstract float getTrimFromEnd()
```

Xác định khoảng thời gian sẽ bị loại bỏ từ cuối media trong quá trình phát, tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời gian cắt cuối 2 giây
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Xác định khoảng thời gian sẽ bị loại bỏ từ cuối media trong quá trình phát, tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời gian cắt cuối 2 giây
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getCaptionTracks() {#getCaptionTracks--}
```
public abstract ICaptionsCollection getCaptionTracks()
```

Lấy bộ sưu tập phụ đề đóng liên quan đến khung âm thanh. Thuộc tính này chỉ đọc và trả về một [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) chứa tất cả các track phụ đề.

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
>             // Lưu dữ liệu nhị phân của track phụ đề dưới dạng tệp .vtt
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

**Trả về:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)