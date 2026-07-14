---
title: IPictureFillFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 그림 채우기 스타일을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ipicturefillformat/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

그림 채우기 스타일을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDpi()](#getDpi--) | 그림을 채우는 데 사용되는 dpi를 반환하거나 설정합니다. |
| [setDpi(int value)](#setDpi-int-) | 그림을 채우는 데 사용되는 dpi를 반환하거나 설정합니다. |
| [getPictureFillMode()](#getPictureFillMode--) | 그림 채우기 모드를 반환하거나 설정합니다. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | 그림 채우기 모드를 반환하거나 설정합니다. |
| [getPicture()](#getPicture--) | 그림을 반환합니다. |
| [getCropLeft()](#getCropLeft--) | 실제 이미지 너비의 퍼센트 중 왼쪽에서 잘라낸 비율을 반환하거나 설정합니다. |
| [setCropLeft(float value)](#setCropLeft-float-) | 실제 이미지 너비의 퍼센트 중 왼쪽에서 잘라낸 비율을 반환하거나 설정합니다. |
| [getCropTop()](#getCropTop--) | 실제 이미지 높이의 퍼센트 중 위쪽에서 잘라낸 비율을 반환하거나 설정합니다. |
| [setCropTop(float value)](#setCropTop-float-) | 실제 이미지 높이의 퍼센트 중 위쪽에서 잘라낸 비율을 반환하거나 설정합니다. |
| [getCropRight()](#getCropRight--) | 실제 이미지 너비의 퍼센트 중 오른쪽에서 잘라낸 비율을 반환하거나 설정합니다. |
| [setCropRight(float value)](#setCropRight-float-) | 실제 이미지 너비의 퍼센트 중 오른쪽에서 잘라낸 비율을 반환하거나 설정합니다. |
| [getCropBottom()](#getCropBottom--) | 실제 이미지 높이의 퍼센트 중 아래쪽에서 잘라낸 비율을 반환하거나 설정합니다. |
| [setCropBottom(float value)](#setCropBottom-float-) | 실제 이미지 높이의 퍼센트 중 아래쪽에서 잘라낸 비율을 반환하거나 설정합니다. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | 쉐이프 경계 상자의 왼쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자를 반환하거나 설정합니다. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | 쉐이프 경계 상자의 왼쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자를 반환하거나 설정합니다. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | 쉐이프 경계 상자의 위쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 위쪽 가장자를 반환하거나 설정합니다. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | 쉐이프 경계 상자의 위쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 위쪽 가장자를 반환하거나 설정합니다. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | 쉐이프 경계 상자의 오른쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 반환하거나 설정합니다. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | 쉐이프 경계 상자의 오른쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 반환하거나 설정합니다. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | 쉐이프 경계 상자의 아래쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 아래쪽 가장자를 반환하거나 설정합니다. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | 쉐이프 경계 상자의 아래쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 아래쪽 가장자를 반환하거나 설정합니다. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | 채우기 그림의 잘라낸 영역을 삭제합니다. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | 쉐이프 크기 및 지정된 해상도에 따라 이미지의 크기를 줄여 압축합니다. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | 쉐이프 크기 및 지정된 해상도에 따라 이미지의 크기를 줄여 압축합니다. |
| [getTileOffsetX()](#getTileOffsetX--) | 텍스처의 수평 오프셋을 쉐이프 원점에서 포인트 단위로 반환하거나 설정합니다. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | 텍스처의 수평 오프셋을 쉐이프 원점에서 포인트 단위로 반환하거나 설정합니다. |
| [getTileOffsetY()](#getTileOffsetY--) | 텍스처의 수직 오프셋을 쉐이프 원점에서 포인트 단위로 반환하거나 설정합니다. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | 텍스처의 수직 오프셋을 쉐이프 원점에서 포인트 단위로 반환하거나 설정합니다. |
| [getTileScaleX()](#getTileScaleX--) | 텍스처 채우기의 수평 스케일을 퍼센트로 반환하거나 설정합니다. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | 텍스처 채우기의 수평 스케일을 퍼센트로 반환하거나 설정합니다. |
| [getTileScaleY()](#getTileScaleY--) | 텍스처 채우기의 수직 스케일을 퍼센트로 반환하거나 설정합니다. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | 텍스처 채우기의 수직 스케일을 퍼센트로 반환하거나 설정합니다. |
| [getTileAlignment()](#getTileAlignment--) | 텍스처가 쉐이프 내에서 정렬되는 방식을 반환하거나 설정합니다. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | 텍스처가 쉐이프 내에서 정렬되는 방식을 반환하거나 설정합니다. |
| [getTileFlip()](#getTileFlip--) | 텍스처 타일을 수평, 수직 또는 양축을 기준으로 뒤집습니다. |
| [setTileFlip(int value)](#setTileFlip-int-) | 텍스처 타일을 수평, 수직 또는 양축을 기준으로 뒤집습니다. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

그림을 채우는 데 사용되는 dpi를 반환하거나 설정합니다. 읽기/쓰기 int.

**반환:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

그림을 채우는 데 사용되는 dpi를 반환하거나 설정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

그림 채우기 모드를 반환하거나 설정합니다. 읽기/쓰기 [PictureFillMode](../../com.aspose.slides/picturefillmode).

**반환:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

그림 채우기 모드를 반환하거나 설정합니다. 읽기/쓰기 [PictureFillMode](../../com.aspose.slides/picturefillmode).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

그림을 반환합니다. 읽기 전용 [ISlidesPicture](../../com.aspose.slides/islidespicture).

**반환:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

실제 이미지 너비의 퍼센트 중 왼쪽에서 잘라낸 비율을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

실제 이미지 너비의 퍼센트 중 왼쪽에서 잘라낸 비율을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

실제 이미지 높이의 퍼센트 중 위쪽에서 잘라낸 비율을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

실제 이미지 높이의 퍼센트 중 위쪽에서 잘라낸 비율을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

실제 이미지 너비의 퍼센트 중 오른쪽에서 잘라낸 비율을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

실제 이미지 너비의 퍼센트 중 오른쪽에서 잘라낸 비율을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

실제 이미지 높이의 퍼센트 중 아래쪽에서 잘라낸 비율을 반환하거나 설정합니다. 읽기/쓰기 float.

**반환:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

실제 이미지 높이의 퍼센트 중 아래쪽에서 잘라낸 비율을 반환하거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

쉐이프 경계 상자의 왼쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자를 반환하거나 설정합니다. 양의 백분율은 안쪽 여백을, 음의 백분율은 바깥쪽 여백을 지정합니다. 읽기/쓰기 float.

**반환:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

쉐이프 경계 상자의 왼쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 왼쪽 가장자를 반환하거나 설정합니다. 양의 백분율은 안쪽 여백을, 음의 백분율은 바깥쪽 여백을 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

쉐이프 경계 상자의 위쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 위쪽 가장자를 반환하거나 설정합니다. 양의 백분율은 안쪽 여백을, 음의 백분율은 바깥쪽 여백을 지정합니다. 읽기/쓰기 float.

**반환:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

쉐이프 경계 상자의 위쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 위쪽 가장자를 반환하거나 설정합니다. 양의 백분율은 안쪽 여백을, 음의 백분율은 바깥쪽 여백을 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

쉐이프 경계 상자의 오른쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 반환하거나 설정합니다. 양의 백분율은 안쪽 여백을, 음의 백분율은 바깥쪽 여백을 지정합니다. 읽기/쓰기 float.

**반환:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

쉐이프 경계 상자의 오른쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 오른쪽 가장자를 반환하거나 설정합니다. 양의 백분율은 안쪽 여백을, 음의 백분율은 바깥쪽 여백을 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

쉐이프 경계 상자의 아래쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 아래쪽 가장자를 반환하거나 설정합니다. 양의 백분율은 안쪽 여백을, 음의 백분율은 바깥쪽 여백을 지정합니다. 읽기/쓰기 float.

**반환:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

쉐이프 경계 상자의 아래쪽 가장자리로부터 백분율 오프셋으로 정의된 채우기 사각형의 아래쪽 가장자를 반환하거나 설정합니다. 양의 백분율은 안쪽 여백을, 음의 백분율은 바깥쪽 여백을 지정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

채우기 그림의 잘라낸 영역을 삭제합니다.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // PictureFrame을 가져옵니다
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // PictureFrame 이미지의 잘라낸 영역을 삭제합니다
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**반환:**
[IPPImage](../../com.aspose.slides/ippimage) - 잘라낸 이미지 또는 자르기가 필요하지 않은 경우 원본 이미지.

--------------------

이 메서드는 WMF/EMF 메타파일을 크롭하면서 래스터 PNG 이미지로 변환합니다.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

이미지를 쉐이프 크기 및 지정된 해상도에 따라 크기를 줄여 압축합니다. 선택적으로 잘라낸 영역도 삭제합니다.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` 프레젠테이션에서 이미지의 크기를 목표 해상도로 설정하고 잘라낸 영역을 제거하여 크기를 줄이는 메서드:
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
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> 다음 예제는 ```
> CompressImage
> ```
 메서드를 사용하여 프레젠테이션에서 이미지의 크기를 목표 해상도로 설정하고 잘라낸 영역을 제거하는 방법을 보여줍니다:
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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | true이면 메서드가 이미지의 잘라낸 영역을 제거하여 크기를 더 줄일 수 있습니다. |
| resolution | float | DPI 단위의 목표 해상도이며, 이 값은 양수여야 하며 이미지가 어떻게 크기 조정되는지를 정의합니다. |

--------------------

이 메서드는 PowerPoint의 "Picture Format -> Compress Pictures" 기능과 유사하게 이미지의 크기와 해상도를 변경합니다. |

**반환:**
boolean - 이미지가 성공적으로 압축되었는지를 나타내는 부울 값입니다. 이미지가 크기 조정되거나 잘라낸 경우 true, 그렇지 않으면 false를 반환합니다.
### getTileOffsetX() {#getTileOffsetX--}
```
public abstract float getTileOffsetX()
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
public abstract void setTileOffsetX(float value)
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
public abstract float getTileOffsetY()
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
public abstract void setTileOffsetY(float value)
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
>      // Sets the vertical offset of the texture to -50
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
public abstract float getTileScaleX()
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
public abstract void setTileScaleX(float value)
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
public abstract float getTileScaleY()
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
public abstract void setTileScaleY(float value)
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
public abstract byte getTileAlignment()
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
public abstract void setTileAlignment(byte value)
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
public abstract int getTileFlip()
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
public abstract void setTileFlip(int value)
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

기본값은 [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |