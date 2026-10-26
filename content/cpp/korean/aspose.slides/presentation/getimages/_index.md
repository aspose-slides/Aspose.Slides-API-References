---
title: GetImages()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션의 모든 슬라이드에 대한 Image 객체를 반환합니다.
type: docs
weight: 456
url: /ko/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) 메서드


프레젠테이션의 모든 슬라이드에 대한 Image 객체를 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 옵션. |

### 반환값

Image 객체.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) 메서드


지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 옵션. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치 배열이며, 1부터 시작합니다. |

### 반환값

Image 객체.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 메서드


사용자 지정 스케일링을 적용한 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 옵션. |
| scaleX | **float** | x축 방향으로 이 썸네일을 스케일링할 값입니다. |
| scaleY | **float** | y축 방향으로 이 썸네일을 스케일링할 값입니다. |

### 반환값

Image 객체.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) 메서드


사용자 지정 스케일링을 적용한 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 옵션. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치 배열이며, 1부터 시작합니다. |
| scaleX | **float** | x축 방향으로 이 썸네일을 스케일링할 값입니다. |
| scaleY | **float** | y축 방향으로 이 썸네일을 스케일링할 값입니다. |

### 반환값

Image 객체.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 메서드


지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 옵션. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기. |

### 반환값

Image 객체.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) 메서드


지정된 크기로 프레젠테이션의 지정된 슬라이드에 대한 썸네일 Image 객체를 반환합니다.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff 옵션. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치 배열이며, 1부터 시작합니다. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기. |

### 반환값

Image 객체.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [Presentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)