---
title: GetImage()
second_title: Tham chiếu API Aspose.Slides cho C++
description: Trả về đối tượng hình ảnh với tỷ lệ tùy chỉnh.
type: docs
weight: 105
url: /vi/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) phương thức

Trả về đối tượng Image với tỷ lệ tùy chỉnh.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### Tham số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| scaleX | **float** | Giá trị dùng để thay đổi tỷ lệ Thumbnail này theo hướng trục x. |
| scaleY | **float** | Giá trị dùng để thay đổi tỷ lệ Thumbnail này theo hướng trục y. |

### Giá trị trả về

đối tượng Image [IImage](../../iimage/)

## ISlide::GetImage() phương thức

Trả về đối tượng Thumbnail Image (20% kích thước thực).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### Giá trị trả về

đối tượng Image [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) phương thức

Trả về đối tượng Image với kích thước được chỉ định.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### Tham số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Kích thước của ảnh cần tạo. |

### Giá trị trả về

đối tượng Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) phương thức

Trả về đối tượng Thumbnail tiff bitmap với các tham số được chỉ định.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### Tham số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tùy chọn Tiff. |

### Giá trị trả về

đối tượng Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) phương thức

Trả về đối tượng Thumbnail Bitmap.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Tham số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tùy chọn Rendering. |

### Giá trị trả về

đối tượng Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) phương thức

Trả về đối tượng Thumbnail Bitmap với tỷ lệ tùy chỉnh.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Tham số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tùy chọn Rendering. |
| scaleX | **float** | Giá trị dùng để thay đổi tỷ lệ Thumbnail này theo hướng trục x. |
| scaleY | **float** | Giá trị dùng để thay đổi tỷ lệ Thumbnail này theo hướng trục y. |

### Giá trị trả về

đối tượng Image [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) phương thức

Trả về đối tượng Thumbnail Bitmap với kích thước được chỉ định.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Tham số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tùy chọn Rendering. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Kích thước của ảnh cần tạo. |

### Giá trị trả về

đối tượng Image [IImage](../../iimage/)

## Xem thêm

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)