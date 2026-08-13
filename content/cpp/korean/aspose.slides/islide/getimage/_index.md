---
title: GetImage()
second_title: Aspose.Slides for C++ API 참조
description: 사용자 지정 스케일링으로 이미지 객체를 반환합니다.
type: docs
weight: 105
url: /ko/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) 메서드

사용자 지정 스케일링으로 이미지 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| scaleX | **float** | x축 방향으로 이 썸네일을 스케일링하는 값입니다. |
| scaleY | **float** | y축 방향으로 이 썸네일을 스케일링하는 값입니다. |

### 반환값

이미지 객체 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() 메서드

실제 크기의 20%인 썸네일 이미지 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### 반환값

이미지 객체 [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) 메서드

지정된 크기의 이미지 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기입니다. |

### 반환값

Bitmap 객체.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) 메서드

지정된 매개변수로 썸네일 tiff 비트맵 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff 옵션. |

### 반환값

이미지 객체.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) 메서드

썸네일 비트맵 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |

### 반환값

Bitmap 객체들.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 메서드

사용자 지정 스케일링으로 썸네일 비트맵 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
| scaleX | **float** | x축 방향으로 이 썸네일을 스케일링하는 값입니다. |
| scaleY | **float** | y축 방향으로 이 썸네일을 스케일링하는 값입니다. |

### 반환값

Bitmap 객체들.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 메서드

지정된 크기로 썸네일 비트맵 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기입니다. |

### 반환값

Bitmap 객체들.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IImage](../../iimage/)
* 클래스 [ISlide](../)
* 클래스 [Size](../../../system.drawing/size/)
* 클래스 [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* 클래스 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)