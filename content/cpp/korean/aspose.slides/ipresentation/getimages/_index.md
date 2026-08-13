---
title: GetImages()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.
type: docs
weight: 417
url: /ko/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) method

프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |

### 반환 값

Bitmap 객체.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) method

지정된 슬라이드에 대한 썸네일 Bitmap 객체를 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치(1부터 시작)의 배열. |

### 반환 값

Bitmap 객체.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method

사용자 지정 스케일링으로 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
| scaleX | **float** | x축 방향으로 이 썸네일을 스케일링할 값. |
| scaleY | **float** | y축 방향으로 이 썸네일을 스케일링할 값. |

### 반환 값

Bitmap 객체.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) method

사용자 지정 스케일링으로 지정된 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치(1부터 시작)의 배열. |
| scaleX | **float** | x축 방향으로 이 썸네일을 스케일링할 값. |
| scaleY | **float** | y축 방향으로 이 썸네일을 스케일링할 값. |

### 반환 값

Bitmap 객체.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method

지정된 크기로 프레젠테이션의 모든 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기. |

### 반환 값

Bitmap 객체.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) method

지정된 크기로 지정된 슬라이드에 대한 썸네일 이미지 객체를 반환합니다.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치(1부터 시작)의 배열. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기. |

### 반환 값

Bitmap 객체.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IImage](../../iimage/)
* 클래스 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 클래스 [IPresentation](../)
* 클래스 [Size](../../../system.drawing/size/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)