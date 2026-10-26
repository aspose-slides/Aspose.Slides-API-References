---
title: AudioFrame
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho một đoạn âm thanh trên một slide.
type: docs
url: /vi/com.aspose.slides/audioframe/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape), [com.aspose.slides.PictureFrame](../../com.aspose.slides/pictureframe)

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IAudioFrame](../../com.aspose.slides/iaudioframe)
```
public class AudioFrame extends PictureFrame implements IAudioFrame
```

Đại diện cho một đoạn âm thanh trên một slide.

--------------------

> ```
> The following examples shows how to change Audio Play Options.
>   
>  Presentation pres = new Presentation("AudioFrameEmbed_out.pptx");
>  try {
>      // Lấy hình dạng AudioFrame
>      AudioFrame audioFrame = (AudioFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Đặt chế độ phát để phát khi nhấp chuột
>      audioFrame.setPlayMode(AudioPlayModePreset.OnClick);
>      // Đặt âm lượng thành Thấp
>      audioFrame.setVolume(AudioVolumeMode.Low);
>      // Đặt âm thanh phát xuyên qua các slide
>      audioFrame.setPlayAcrossSlides(true);
>      // Tắt vòng lặp cho âm thanh
>      audioFrame.setPlayLoopMode(false);
>      // Ẩn AudioFrame trong khi trình chiếu
>      audioFrame.setHideAtShowing(true);
>      // Quay lại đầu âm thanh sau khi phát
>      audioFrame.setRewindAudio(true);
>      // Lưu tệp PowerPoint vào đĩa
>      pres.save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAudioCdStartTrack()](#getAudioCdStartTrack--) | Trả về hoặc thiết lập chỉ mục track bắt đầu. |
| [setAudioCdStartTrack(int value)](#setAudioCdStartTrack-int-) | Trả về hoặc thiết lập chỉ mục track bắt đầu. |
| [getAudioCdStartTrackTime()](#getAudioCdStartTrackTime--) | Trả về hoặc thiết lập thời gian track bắt đầu. |
| [setAudioCdStartTrackTime(int value)](#setAudioCdStartTrackTime-int-) | Trả về hoặc thiết lập thời gian track bắt đầu. |
| [getAudioCdEndTrack()](#getAudioCdEndTrack--) | Trả về hoặc thiết lập chỉ mục track cuối. Đọc/ghi  int . |
| [setAudioCdEndTrack(int value)](#setAudioCdEndTrack-int-) | Trả về hoặc thiết lập chỉ mục track cuối. Đọc/ghi  int . |
| [getAudioCdEndTrackTime()](#getAudioCdEndTrackTime--) | Trả về hoặc thiết lập thời gian track cuối. |
| [setAudioCdEndTrackTime(int value)](#setAudioCdEndTrackTime-int-) | Trả về hoặc thiết lập thời gian track cuối. |
| [getVolume()](#getVolume--) | Trả về hoặc thiết lập âm lượng âm thanh. |
| [setVolume(int value)](#setVolume-int-) | Trả về hoặc thiết lập âm lượng âm thanh. |
| [getPlayMode()](#getPlayMode--) | Trả về hoặc thiết lập chế độ phát âm thanh. |
| [setPlayMode(int value)](#setPlayMode-int-) | Trả về hoặc thiết lập chế độ phát âm thanh. |
| [getHideAtShowing()](#getHideAtShowing--) | Xác định liệu AudioFrame có bị ẩn hay không. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Xác định liệu AudioFrame có bị ẩn hay không. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Xác định liệu âm thanh có được lặp lại hay không. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Xác định liệu âm thanh có được lặp lại hay không. |
| [getPlayAcrossSlides()](#getPlayAcrossSlides--) | Xác định liệu âm thanh đang phát xuyên qua các slide hay không. |
| [setPlayAcrossSlides(boolean value)](#setPlayAcrossSlides-boolean-) | Xác định liệu âm thanh đang phát xuyên qua các slide hay không. |
| [getRewindAudio()](#getRewindAudio--) | Xác định liệu âm thanh có tự động quay lại đầu sau khi phát hay không. |
| [setRewindAudio(boolean value)](#setRewindAudio-boolean-) | Xác định liệu âm thanh có tự động quay lại đầu sau khi phát hay không. |
| [getEmbedded()](#getEmbedded--) | Xác định liệu âm thanh được nhúng vào bản trình chiếu hay không. |
| [getLinkPathLong()](#getLinkPathLong--) | Trả về hoặc thiết lập tên của tệp âm thanh được liên kết tới AudioFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Trả về hoặc thiết lập tên của tệp âm thanh được liên kết tới AudioFrame. |
| [getEmbeddedAudio()](#getEmbeddedAudio--) | Trả về hoặc thiết lập đối tượng âm thanh nhúng. |
| [setEmbeddedAudio(IAudio value)](#setEmbeddedAudio-com.aspose.slides.IAudio-) | Trả về hoặc thiết lập đối tượng âm thanh nhúng. |
| [getFadeInDuration()](#getFadeInDuration--) | Xác định thời gian kéo dài cho hiệu ứng fade-in ban đầu của media tính bằng mili giây. |
| [setFadeInDuration(float value)](#setFadeInDuration-float-) | Xác định thời gian kéo dài cho hiệu ứng fade-in ban đầu của media tính bằng mili giây. |
| [getFadeOutDuration()](#getFadeOutDuration--) | Xác định thời gian kéo dài cho fade-out cuối cùng của media tính bằng mili giây. |
| [setFadeOutDuration(float value)](#setFadeOutDuration-float-) | Xác định thời gian kéo dài cho fade-out cuối cùng của media tính bằng mili giây. |
| [getVolumeValue()](#getVolumeValue--) | Trả về hoặc thiết lập âm lượng âm thanh tính bằng phần trăm. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Trả về hoặc thiết lập âm lượng âm thanh tính bằng phần trăm. |
| [getTrimFromStart()](#getTrimFromStart--) | Xác định thời gian cần loại bỏ từ đầu media trong quá trình phát, tính bằng mili giây. |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Xác định thời gian cần loại bỏ từ đầu media trong quá trình phát, tính bằng mili giây. |
| [getTrimFromEnd()](#getTrimFromEnd--) | Xác định thời gian cần loại bỏ từ cuối media trong quá trình phát, tính bằng mili giây. |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Xác định thời gian cần loại bỏ từ cuối media trong quá trình phát, tính bằng mili giây. |
| [getCaptionTracks()](#getCaptionTracks--) | Lấy bộ sưu tập các phụ đề đóng liên quan đến audio frame. |

### getAudioCdStartTrack() {#getAudioCdStartTrack--}
```
public final int getAudioCdStartTrack()
```

Trả về hoặc thiết lập chỉ mục track bắt đầu. Đọc/ghi  int .

**Trả về:**
int

### setAudioCdStartTrack(int value) {#setAudioCdStartTrack-int-}
```
public final void setAudioCdStartTrack(int value)
```

Trả về hoặc thiết lập chỉ mục track bắt đầu. Đọc/ghi  int .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAudioCdStartTrackTime() {#getAudioCdStartTrackTime--}
```
public final int getAudioCdStartTrackTime()
```

Trả về hoặc thiết lập thời gian track bắt đầu. Đọc/ghi  int .

**Trả về:**
int

### setAudioCdStartTrackTime(int value) {#setAudioCdStartTrackTime-int-}
```
public final void setAudioCdStartTrackTime(int value)
```

Trả về hoặc thiết lập thời gian track bắt đầu. Đọc/ghi  int .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrack() {#getAudioCdEndTrack--}
```
public final int getAudioCdEndTrack()
```

Trả về hoặc thiết lập chỉ mục track cuối. Đọc/ghi  int .

**Trả về:**
int

### setAudioCdEndTrack(int value) {#setAudioCdEndTrack-int-}
```
public final void setAudioCdEndTrack(int value)
```

Trả về hoặc thiết lập chỉ mục track cuối. Đọc/ghi  int .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAudioCdEndTrackTime() {#getAudioCdEndTrackTime--}
```
public final int getAudioCdEndTrackTime()
```

Trả về hoặc thiết lập thời gian track cuối. Đọc/ghi  int .

**Trả về:**
int

### setAudioCdEndTrackTime(int value) {#setAudioCdEndTrackTime-int-}
```
public final void setAudioCdEndTrackTime(int value)
```

Trả về hoặc thiết lập thời gian track cuối. Đọc/ghi  int .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getVolume() {#getVolume--}
```
public final int getVolume()
```

Trả về hoặc thiết lập âm lượng âm thanh. Đọc/ghi [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Trả về:**
int

### setVolume(int value) {#setVolume-int-}
```
public final void setVolume(int value)
```

Trả về hoặc thiết lập âm lượng âm thanh. Đọc/ghi [AudioVolumeMode](../../com.aspose.slides/audiovolumemode).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPlayMode() {#getPlayMode--}
```
public final int getPlayMode()
```

Trả về hoặc thiết lập chế độ phát âm thanh. Đọc/ghi [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Trả về:**
int

### setPlayMode(int value) {#setPlayMode-int-}
```
public final void setPlayMode(int value)
```

Trả về hoặc thiết lập chế độ phát âm thanh. Đọc/ghi [AudioPlayModePreset](../../com.aspose.slides/audioplaymodepreset).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public final boolean getHideAtShowing()
```

Xác định liệu AudioFrame có bị ẩn hay không. Đọc/ghi  boolean .

**Trả về:**
boolean

### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public final void setHideAtShowing(boolean value)
```

Xác định liệu AudioFrame có bị ẩn hay không. Đọc/ghi  boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public final boolean getPlayLoopMode()
```

Xác định liệu âm thanh có được lặp lại hay không. Đọc/ghi  boolean .

**Trả về:**
boolean

### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public final void setPlayLoopMode(boolean value)
```

Xác định liệu âm thanh có được lặp lại hay không. Đọc/ghi  boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPlayAcrossSlides() {#getPlayAcrossSlides--}
```
public final boolean getPlayAcrossSlides()
```

Xác định liệu âm thanh đang phát xuyên qua các slide hay không. Đọc/ghi  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Thêm khung âm thanh
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Đặt Audio để phát xuyên qua các slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Đặt Audio để tự động tua lại về đầu sau khi phát
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
public final void setPlayAcrossSlides(boolean value)
```

Xác định liệu âm thanh đang phát xuyên qua các slide hay không. Đọc/ghi  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Thêm khung âm thanh
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Đặt Audio để phát xuyên qua các slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Đặt Audio để tự động tua lại về đầu sau khi phát
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
public final boolean getRewindAudio()
```

Xác định liệu âm thanh có tự động quay lại đầu sau khi phát hay không. Đọc/ghi  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Thêm khung âm thanh
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Đặt Audio để phát xuyên qua các slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Đặt Audio để tự động tua lại về đầu sau khi phát
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
public final void setRewindAudio(boolean value)
```

Xác định liệu âm thanh có tự động quay lại đầu sau khi phát hay không. Đọc/ghi  boolean .

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       // Thêm khung âm thanh
>       IAudioFrame audioFrame = slide.getShapes().addAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");
>       // Đặt Audio để phát xuyên qua các slide
>       audioFrame.setPlayAcrossSlides(true);
>       // Đặt Audio để tự động tua lại về đầu sau khi phát
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
public final boolean getEmbedded()
```

Xác định liệu âm thanh được nhúng vào bản trình chiếu hay không. Chỉ đọc  boolean .

**Trả về:**
boolean

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Trả về hoặc thiết lập tên của tệp âm thanh được liên kết tới AudioFrame. Đọc/ghi String.

**Trả về:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Trả về hoặc thiết lập tên của tệp âm thanh được liên kết tới AudioFrame. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedAudio() {#getEmbeddedAudio--}
```
public final IAudio getEmbeddedAudio()
```

Trả về hoặc thiết lập đối tượng âm thanh nhúng. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

**Trả về:**
[IAudio](../../com.aspose.slides/iaudio)

### setEmbeddedAudio(IAudio value) {#setEmbeddedAudio-com.aspose.slides.IAudio-}
```
public final void setEmbeddedAudio(IAudio value)
```

Trả về hoặc thiết lập đối tượng âm thanh nhúng. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getFadeInDuration() {#getFadeInDuration--}
```
public final float getFadeInDuration()
```

Xác định thời gian kéo dài cho fade-in ban đầu của media tính bằng mili giây. Đọc/ghi float.

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
>      pres.save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
float

### setFadeInDuration(float value) {#setFadeInDuration-float-}
```
public final void setFadeInDuration(float value)
```

Xác định thời gian kéo dài cho fade-in ban đầu của media tính bằng mili giây. Đọc/ghi float.

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
public final float getFadeOutDuration()
```

Xác định thời gian kéo dài cho fade-out cuối cùng của media tính bằng mili giây. Đọc/ghi float.

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
public final void setFadeOutDuration(float value)
```

Xác định thời gian kéo dài cho fade-out cuối cùng của media tính bằng mili giây. Đọc/ghi float.

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
public final float getVolumeValue()
```

Trả về hoặc thiết lập âm lượng âm thanh tính bằng phần trăm. Đọc/ghi float.

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
>      pres.save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
float

### setVolumeValue(float value) {#setVolumeValue-float-}
```
public final void setVolumeValue(float value)
```

Trả về hoặc thiết lập âm lượng âm thanh tính bằng phần trăm. Đọc/ghi float.

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
public final float getTrimFromStart()
```

Xác định thời gian cần loại bỏ từ đầu media trong quá trình phát, tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời gian cắt đầu là 1.5 giây
>      audioFrame.setTrimFromStart(1500f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
float

### setTrimFromStart(float value) {#setTrimFromStart-float-}
```
public final void setTrimFromStart(float value)
```

Xác định thời gian cần loại bỏ từ đầu media trong quá trình phát, tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời gian cắt đầu là 1.5 giây
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
public final float getTrimFromEnd()
```

Xác định thời gian cần loại bỏ từ cuối media trong quá trình phát, tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời gian cắt cuối là 2 giây
>      audioFrame.setTrimFromEnd(2000f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
float

### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public final void setTrimFromEnd(float value)
```

Xác định thời gian cần loại bỏ từ cuối media trong quá trình phát, tính bằng mili giây. Đọc/ghi float.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream audioStream = new FileInputStream("sampleaudio.mp3");
>      IAudio audio = pres.getAudios().addAudio(audioStream, LoadingStreamBehavior.ReadStreamAndRelease);
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(50, 50, 100, 100, audio);
>      // Đặt thời gian cắt cuối là 2 giây
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
public final ICaptionsCollection getCaptionTracks()
```

Lấy bộ sưu tập các phụ đề đóng liên quan đến audio frame. Thuộc tính này chỉ đọc và trả về một [ICaptionsCollection](../../com.aspose.slides/icaptionscollection) chứa tất cả các track phụ đề.

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
>              // Lưu dữ liệu nhị phân của track phụ đề thành tệp .vtt
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

**Trả về:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)