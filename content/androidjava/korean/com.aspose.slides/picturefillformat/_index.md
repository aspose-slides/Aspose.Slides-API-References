---
title: PictureFillFormat
second_title: Android용 Aspose.Slides Java API 레퍼런스
description: 그림 채우기 스타일을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/picturefillformat/
---
**상속:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**모든 구현된 인터페이스:**  
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)  
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

그림 채우기 스타일을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | 그림을 채우는 데 사용되는 dpi를 반환하거나 설정합니다. |
| [setDpi(int value)](#setDpi-int-) | 그림을 채우는 데 사용되는 dpi를 반환하거나 설정합니다. |
| [getPictureFillMode()](#getPictureFillMode--) | 그림 채우기 모드를 반환하거나 설정합니다. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | 그림 채우기 모드를 반환하거나 설정합니다. |
| [getPicture()](#getPicture--) | 그림을 반환합니다. |
| [getCropLeft()](#getCropLeft--) | 그림의 왼쪽에서 잘라낸 실제 이미지 너비 백분율을 반환하거나 설정합니다. |
| [setCropLeft(float value)](#setCropLeft-float-) | 그림의 왼쪽에서 잘라낸 실제 이미지 너비 백분율을 반환하거나 설정합니다. |
| [getCropTop()](#getCropTop--) | 그림의 상단에서 잘라낸 실제 이미지 높이 백분율을 반환하거나 설정합니다. |
| [setCropTop(float value)](#setCropTop-float-) | 그림의 상단에서 잘라낸 실제 이미지 높이 백분율을 반환하거나 설정합니다. |
| [getCropRight()](#getCropRight--) | 그림의 오른쪽에서 잘라낸 실제 이미지 너비 백분율을 반환하거나 설정합니다. |
| [setCropRight(float value)](#setCropRight-float-) | 그림의 오른쪽에서 잘라낸 실제 이미지 너비 백분율을 반환하거나 설정합니다. |
| [getCropBottom()](#getCropBottom--) | 그림의 아래쪽에서 잘라낸 실제 이미지 높이 백분율을 반환하거나 설정합니다. |
| [setCropBottom(float value)](#setCropBottom-float-) | 그림의 아래쪽에서 잘라낸 실제 이미지 높이 백분율을 반환하거나 설정합니다. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 채워진 그림의 잘라낸 영역을 삭제합니다. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | 지정된 해상도와 도형 크기를 기반으로 이미지 크기를 줄여 압축합니다. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | 지정된 해상도와 도형 크기를 기반으로 이미지 크기를 줄여 압축합니다. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | 도형 경계 상자의 왼쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자리를 반환하거나 설정합니다. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | 도형 경계 상자의 왼쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자리를 반환하거나 설정합니다. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | 도형 경계 상자의 위쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 위쪽 가장자리를 반환하거나 설정합니다. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | 도형 경계 상자의 위쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 위쪽 가장자를 반환하거나 설정합니다. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | 도형 경계 상자의 오른쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 반환하거나 설정합니다. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | 도형 경계 상자의 오른쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 반환하거나 설정합니다. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | 도형 경계 상자의 아래쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 아래쪽 가장자를 반환하거나 설정합니다. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | 도형 경계 상자의 아래쪽 가장자리에서 백분율 오프셋으로 정의된 채우기 사각형의 아래쪽 가장자를 반환하거나 설정합니다. |
| [getTileOffsetX()](#getTileOffsetX--) | 도형 원점으로부터 텍스처의 수평 오프셋을 포인트 단위로 반환하거나 설정합니다. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | 도형 원점으로부터 텍스처의 수평 오프셋을 포인트 단위로 반환하거나 설정합니다. |
| [getTileOffsetY()](#getTileOffsetY--) | 도형 원점으로부터 텍스처의 수직 오프셋을 포인트 단위로 반환하거나 설정합니다. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | 도형 원점으로부터 텍스처의 수직 오프셋을 포인트 단위로 반환하거나 설정합니다. |
| [getTileScaleX()](#getTileScaleX--) | 텍스처 채우기의 수평 스케일을 백분율로 반환하거나 설정합니다. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | 텍스처 채우기의 수평 스케일을 백분율로 반환하거나 설정합니다. |
| [getTileScaleY()](#getTileScaleY--) | 텍스처 채우기의 수직 스케일을 백분율로 반환하거나 설정합니다. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | 텍스처 채우기의 수직 스케일을 백분율로 반환하거나 설정합니다. |
| [getTileAlignment()](#getTileAlignment--) | 텍스처가 도형 내부에서 어떻게 정렬되는지를 반환하거나 설정합니다. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | 텍스처가 도형 내부에서 어떻게 정렬되는지를 반환하거나 설정합니다. |
| [getTileFlip()](#getTileFlip--) | 텍스처 타일을 수평, 수직 또는 두 축 모두를 기준으로 뒤집습니다. |
| [setTileFlip(int value)](#setTileFlip-int-) | 텍스처 타일을 수평, 수직 또는 두 축 모두를 기준으로 뒤집습니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환:**
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

그림을 채우는 데 사용되는 dpi를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

그림을 채우는 데 사용되는 dpi를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

그림 채우기 모드를 반환하거나 설정합니다. 읽기/쓰기 [PictureFillMode](../../com.aspose.slides/picturefillmode).

**반환:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

그림 채우기 모드를 반환하거나 설정합니다. 읽기/쓰기 [PictureFillMode](../../com.aspose.slides/picturefillmode).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

그림을 반환합니다. 읽기 전용 [ISlidesPicture](../../com.aspose.slides/islidespicture).

**반환:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

그림의 왼쪽에서 잘라낸 실제 이미지 너비 백분율을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

그림의 왼쪽에서 잘라낸 실제 이미지 너비 백분율을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

그림의 상단에서 잘라낸 실제 이미지 높이 백분율을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

그림의 상단에서 잘라낸 실제 이미지 높이 백분율을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

그림의 오른쪽에서 잘라낸 실제 이미지 너비 백분율을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

그림의 오른쪽에서 잘라낸 실제 이미지 너비 백분율을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

그림의 아래쪽에서 잘라낸 실제 이미지 높이 백분율을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

그림의 아래쪽에서 잘라낸 실제 이미지 높이 백분율을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

채워진 그림의 잘라낸 영역을 삭제합니다.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Deletes cropped areas of the PictureFrame image
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**
[IPPImage](../../com.aspose.slides/ippimage) - 잘라낸 이미지 또는 자르기가 필요하지 않은 경우 원본 이미지.

--------------------

이 메서드는 WMF/EMF 메타파일을 잘라내면서 래스터 PNG 이미지로 변환합니다.

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

지정된 해상도와 도형 크기를 기반으로 이미지 크기를 줄여 압축합니다. 선택적으로 잘라낸 영역도 삭제합니다.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` 프레젠테이션에서 이미지 크기를 목표 해상도로 설정하고 잘라낸 영역을 제거하여 이미지 크기를 줄이는 메서드:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | int | The target resolution for compression, specified as a value of the [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> 다음 예제는 ```
> CompressImage
> ```
 메서드를 사용하여 프레젠테이션에서 이미지 크기를 목표 해상도로 설정하고 잘라낸 영역을 제거하여 이미지 크기를 줄이는 방법을 보여줍니다:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | float | The target resolution in DPI. This value must be positive and defines how the image will be resized.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A  boolean  indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public final float getStretchOffsetTop()
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public final void setStretchOffsetTop(float value)
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public final float getStretchOffsetRight()
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public final void setStretchOffsetRight(float value)
```

채우기 사각형의 오른쪽 가장자리를 반환하거나 설정합니다. 이 가장자리는 도형 경계 상자의 오른쪽 가장자리에서 백분율 오프셋으로 정의됩니다. 양수 백분율은 인셋을 지정하고, 음수 백분율은 아웃셋을 지정합니다. 읽기/쓰기  float .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public final float getStretchOffsetBottom()
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final void setStretchOffsetBottom(float value)
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
public final float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public final void setTileScaleX(float value)
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public final float getTileScaleY()
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public final void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileAlignment() {#getTileAlignment--}
```
public final byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public final void setTileAlignment(byte value)
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTileFlip() {#getTileFlip--}
```
public final int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

기본값은 [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip)입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |