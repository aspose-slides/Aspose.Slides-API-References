---
title: IVideoFrame
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị một đoạn video trên slide.
type: docs
url: /vi/com.aspose.slides/ivideoframe/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public interface IVideoFrame extends IPictureFrame
```

Biểu thị một đoạn video trên slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRewindVideo()](#getRewindVideo--) | Xác định xem video có được tự động quay lại đầu khi bộ phim đã phát xong hay không. |
| [setRewindVideo(boolean value)](#setRewindVideo-boolean-) | Xác định xem video có được tự động quay lại đầu khi bộ phim đã phát xong hay không. |
| [getPlayLoopMode()](#getPlayLoopMode--) | Xác định xem video có được lặp lại hay không. |
| [setPlayLoopMode(boolean value)](#setPlayLoopMode-boolean-) | Xác định xem video có được lặp lại hay không. |
| [getHideAtShowing()](#getHideAtShowing--) | Xác định xem VideoFrame có bị ẩn hay không. |
| [setHideAtShowing(boolean value)](#setHideAtShowing-boolean-) | Xác định xem VideoFrame có bị ẩn hay không. |
| [getVolume()](#getVolume--) | Trả về hoặc đặt âm lượng âm thanh. |
| [setVolume(int value)](#setVolume-int-) | Trả về hoặc đặt âm lượng âm thanh. |
| [getVolumeValue()](#getVolumeValue--) | Trả về hoặc đặt âm lượng video chính xác dưới dạng phần trăm. |
| [setVolumeValue(float value)](#setVolumeValue-float-) | Trả về hoặc đặt âm lượng video chính xác dưới dạng phần trăm. |
| [getPlayMode()](#getPlayMode--) | Trả về hoặc đặt chế độ phát video. |
| [setPlayMode(int value)](#setPlayMode-int-) | Trả về hoặc đặt chế độ phát video. |
| [getFullScreenMode()](#getFullScreenMode--) | Xác định xem video có được hiển thị ở chế độ toàn màn hình hay không. |
| [setFullScreenMode(boolean value)](#setFullScreenMode-boolean-) | Xác định xem video có được hiển thị ở chế độ toàn màn hình hay không. |
| [getLinkPathLong()](#getLinkPathLong--) | Trả về hoặc đặt tên của tệp video được liên kết với VideoFrame. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Trả về hoặc đặt tên của tệp video được liên kết với VideoFrame. |
| [getEmbeddedVideo()](#getEmbeddedVideo--) | Trả về hoặc đặt đối tượng video nhúng. |
| [setEmbeddedVideo(IVideo value)](#setEmbeddedVideo-com.aspose.slides.IVideo-) | Trả về hoặc đặt đối tượng video nhúng. |
| [getTrimFromStart()](#getTrimFromStart--) | Cắt đầu [ms] |
| [setTrimFromStart(float value)](#setTrimFromStart-float-) | Cắt đầu [ms] |
| [getTrimFromEnd()](#getTrimFromEnd--) | Cắt cuối [ms] |
| [setTrimFromEnd(float value)](#setTrimFromEnd-float-) | Cắt cuối [ms] |
| [getCaptionTracks()](#getCaptionTracks--) | Lấy bộ sưu tập phụ đề đóng liên quan đến khung âm thanh. |

### getRewindVideo() {#getRewindVideo--}
```
public abstract boolean getRewindVideo()
```

Xác định xem video có được tự động quay lại đầu khi bộ phim đã phát xong hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setRewindVideo(boolean value) {#setRewindVideo-boolean-}
```
public abstract void setRewindVideo(boolean value)
```

Xác định xem video có được tự động quay lại đầu khi bộ phim đã phát xong hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPlayLoopMode() {#getPlayLoopMode--}
```
public abstract boolean getPlayLoopMode()
```

Xác định xem video có được lặp lại hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setPlayLoopMode(boolean value) {#setPlayLoopMode-boolean-}
```
public abstract void setPlayLoopMode(boolean value)
```

Xác định xem video có được lặp lại hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHideAtShowing() {#getHideAtShowing--}
```
public abstract boolean getHideAtShowing()
```

Xác định xem VideoFrame có bị ẩn hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHideAtShowing(boolean value) {#setHideAtShowing-boolean-}
```
public abstract void setHideAtShowing(boolean value)
```

Xác định xem VideoFrame có bị ẩn hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

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

### getVolumeValue() {#getVolumeValue--}
```
public abstract float getVolumeValue()
```

Trả về hoặc đặt âm lượng video chính xác dưới dạng phần trăm. Giá trị được biểu thị dưới dạng phần trăm từ 0 đến 100. Sử dụng thuộc tính này để đọc hoặc đặt các giá trị âm lượng chi tiết hơn so với các mức định sẵn có thông qua thuộc tính Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Đọc/ghi  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Đọc âm lượng chính xác hiện tại và đặt nó thành 75,5 phần trăm.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
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

Trả về hoặc đặt âm lượng video chính xác dưới dạng phần trăm. Giá trị được biểu thị dưới dạng phần trăm từ 0 đến 100. Sử dụng thuộc tính này để đọc hoặc đặt các giá trị âm lượng chi tiết hơn so với các mức định sẵn có thông qua thuộc tính Volume (\#getVolume.getVolume/\#setVolume(int).setVolume(int)). Đọc/ghi  float .

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("video.pptx");
>  try {
>      IVideoFrame videoFrame = (IVideoFrame)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Đọc âm lượng chính xác hiện tại và đặt nó thành 75.5 phần trăm.
>      float currentVolume = videoFrame.getVolumeValue();
>      System.out.println(currentVolume);
>      videoFrame.setVolumeValue(75.5f);
>      pres.save("video_with_volume.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getPlayMode() {#getPlayMode--}
```
public abstract int getPlayMode()
```

Trả về hoặc đặt chế độ phát video. Đọc/ghi [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Trả về:**
int
### setPlayMode(int value) {#setPlayMode-int-}
```
public abstract void setPlayMode(int value)
```

Trả về hoặc đặt chế độ phát video. Đọc/ghi [VideoPlayModePreset](../../com.aspose.slides/videoplaymodepreset).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFullScreenMode() {#getFullScreenMode--}
```
public abstract boolean getFullScreenMode()
```

Xác định xem video có được hiển thị ở chế độ toàn màn hình hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setFullScreenMode(boolean value) {#setFullScreenMode-boolean-}
```
public abstract void setFullScreenMode(boolean value)
```

Xác định xem video có được hiển thị ở chế độ toàn màn hình hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Trả về hoặc đặt tên của tệp video được liên kết với VideoFrame. Đọc/ghi String.

**Trả về:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Trả về hoặc đặt tên của tệp video được liên kết với VideoFrame. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedVideo() {#getEmbeddedVideo--}
```
public abstract IVideo getEmbeddedVideo()
```

Trả về hoặc đặt đối tượng video nhúng. Đọc/ghi [IVideo](../../com.aspose.slides/ivideo).

**Trả về:**
[IVideo](../../com.aspose.slides/ivideo)
### setEmbeddedVideo(IVideo value) {#setEmbeddedVideo-com.aspose.slides.IVideo-}
```
public abstract void setEmbeddedVideo(IVideo value)
```

Trả về hoặc đặt đối tượng video nhúng. Đọc/ghi [IVideo](../../com.aspose.slides/ivideo).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IVideo](../../com.aspose.slides/ivideo) |  |

### getTrimFromStart() {#getTrimFromStart--}
```
public abstract float getTrimFromStart()
```

Cắt đầu [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //đặt thời gian cắt đầu 1 giây
>      videoFrame.setTrimFromStart(1000f);
>      //đặt thời gian cắt kết thúc 2 giây
>      videoFrame.setTrimFromEnd(2000f);
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

Cắt đầu [ms]

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.mp4")));
>      IVideoFrame videoFrame = slide.getShapes().addVideoFrame(0, 0, 100, 100, video);
>      //đặt thời gian cắt đầu 1 giây
>      videoFrame.setTrimFromStart(1000f);
>      //đặt thời gian cắt kết thúc 2 giây
>      videoFrame.setTrimFromEnd(2000f);
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

Cắt cuối [ms]

**Trả về:**
float
### setTrimFromEnd(float value) {#setTrimFromEnd-float-}
```
public abstract void setTrimFromEnd(float value)
```

Cắt cuối [ms]

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
>  Presentation pres = new Presentation("video with captions.pptx");
>  try {
>      for (IShape shape : pres.getSlides().get_Item(0).getShapes())
>      {
>          if (!(shape instanceof IVideoFrame))
>              continue;
>          IVideoFrame videoFrame = (IVideoFrame) shape;
>          for (ICaptions captionTrack : videoFrame.getCaptionTracks())
>          {
>              // Trích xuất dữ liệu nhị phân của phụ đề và lưu chúng vào tệp
>              FileOutputStream fos = new FileOutputStream(captionTrack.getCaptionId() + ".vtt");
>              fos.write(captionTrack.getBinaryData());
>              fos.close();
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
[ICaptionsCollection](../../com.aspose.slides/icaptionscollection)