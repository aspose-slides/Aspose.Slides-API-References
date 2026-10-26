---
title: HyperlinkActionType
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một loại hành động siêu liên kết.
type: docs
url: /vi/com.aspose.slides/hyperlinkactiontype/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HyperlinkActionType extends System.Enum
```

Đại diện cho một loại hành động siêu liên kết.
## Trường

| Field | Description |
| --- | --- |
| [Unknown](#Unknown) | Loại hành động không được nhận dạng. |
| [NoAction](#NoAction) | Không có hành động. |
| [Hyperlink](#Hyperlink) | Siêu liên kết thông thường. |
| [JumpFirstSlide](#JumpFirstSlide) | Chuyển tới slide đầu tiên của bản trình chiếu. |
| [JumpPreviousSlide](#JumpPreviousSlide) | Chuyển tới slide trước. |
| [JumpNextSlide](#JumpNextSlide) | Chuyển tới slide tiếp theo. |
| [JumpLastSlide](#JumpLastSlide) | Chuyển tới slide cuối cùng của bản trình chiếu. |
| [JumpEndShow](#JumpEndShow) | Chuyển tới cuối trình chiếu. |
| [JumpLastViewedSlide](#JumpLastViewedSlide) | Chuyển tới slide đã xem cuối cùng. |
| [JumpSpecificSlide](#JumpSpecificSlide) | Chuyển tới slide cụ thể, được tham chiếu bởi ([IHyperlink.getTargetSlide](../../com.aspose.slides/ihyperlink\#getTargetSlide)) property. |
| [StartCustomSlideShow](#StartCustomSlideShow) | Bắt đầu trình chiếu tùy chỉnh. |
| [OpenFile](#OpenFile) | Mở tệp được tham chiếu. |
| [OpenPresentation](#OpenPresentation) | Mở bản trình chiếu được tham chiếu. |
| [StartStopMedia](#StartStopMedia) | Bắt đầu/dừng phát tệp media. |
| [StartMacro](#StartMacro) | Bắt đầu thực thi script macro. |
| [StartProgram](#StartProgram) | Bắt đầu chương trình. |
### Unknown {#Unknown}
```
public static final int Unknown
```


Unrecognized action type.

### NoAction {#NoAction}
```
public static final int NoAction
```


No action.

### Hyperlink {#Hyperlink}
```
public static final int Hyperlink
```


Usual hyperlink.

### JumpFirstSlide {#JumpFirstSlide}
```
public static final int JumpFirstSlide
```


Jump to the first slide of the presentation.

### JumpPreviousSlide {#JumpPreviousSlide}
```
public static final int JumpPreviousSlide
```


Jump to the previous slide.

### JumpNextSlide {#JumpNextSlide}
```
public static final int JumpNextSlide
```


Jump to the next slide.

### JumpLastSlide {#JumpLastSlide}
```
public static final int JumpLastSlide
```


Jump to the last slide of the presentation.

### JumpEndShow {#JumpEndShow}
```
public static final int JumpEndShow
```


Jump to the end of slideshow.

### JumpLastViewedSlide {#JumpLastViewedSlide}
```
public static final int JumpLastViewedSlide
```


Jump to the last viewed slide.

### JumpSpecificSlide {#JumpSpecificSlide}
```
public static final int JumpSpecificSlide
```


Jump to the specific slide, referred by ([IHyperlink.getTargetSlide](../../com.aspose.slides/ihyperlink\#getTargetSlide)) property.

### StartCustomSlideShow {#StartCustomSlideShow}
```
public static final int StartCustomSlideShow
```


Start custom slideshow.

### OpenFile {#OpenFile}
```
public static final int OpenFile
```


Open referenced file.

### OpenPresentation {#OpenPresentation}
```
public static final int OpenPresentation
```


Open referenced presentation.

### StartStopMedia {#StartStopMedia}
```
public static final int StartStopMedia
```


Start/stop playing mediafile.

### StartMacro {#StartMacro}
```
public static final int StartMacro
```


Start executing macro script.

### StartProgram {#StartProgram}
```
public static final int StartProgram
```


Start program.