---
title: GetImage()
second_title: Aspose.Slides for C++ API 참조
description: 사용자 지정 스케일링으로 이미지 객체를 반환합니다.
type: docs
weight: 105
url: /ko/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) method


사용자 지정 스케일링으로 이미지 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scaleX | **float** | x축 방향으로 이 썸네일을 스케일링하는 값입니다. |
| scaleY | **float** | y축 방향으로 이 썸네일을 스케일링하는 값입니다. |

### 반환값

Image object [IImage](../../iimage/)

## ISlide::GetImage() method


실제 크기의 20%인 썸네일 이미지 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### 반환값

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) method


지정된 크기의 이미지 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기입니다. |

### 반환값

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) method


지정된 매개변수로 썸네일 TIFF 비트맵 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff 옵션. |

### 반환값

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) method


썸네일 비트맵 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |

### 반환값

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method


사용자 지정 스케일링으로 썸네일 비트맵 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
| scaleX | **float** | x축 방향으로 이 썸네일을 스케일링하는 값입니다. |
| scaleY | **float** | y축 방향으로 이 썸네일을 스케일링하는 값입니다. |

### 반환값

Image object [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method


지정된 크기로 썸네일 비트맵 객체를 반환합니다.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기입니다. |

### 반환값

Image object [IImage](../../iimage/)

## 또 다른 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)