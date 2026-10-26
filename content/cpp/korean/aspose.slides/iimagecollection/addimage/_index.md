---
title: AddImage()
second_title: Aspose.Slides for C++ API 참조
description: 프레젠테이션에 이미지를 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) 메서드

프레젠테이션에 이미지를 추가합니다.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | 추가할 이미지. |

### 반환 값

추가된 이미지.

## 비고

이 메서드는 WMF/EMF 메타파일을 프레젠테이션에 삽입하기 전에 래스터 PNG 이미지로 변환합니다.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) 메서드

메모리 스트림에서 이미지를 추가합니다.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | 메모리 스트림. |

### 반환 값

추가된 이미지.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) 메서드

스트림에서 프레젠테이션에 이미지를 추가합니다.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 이미지를 추가할 스트림. |

### 반환 값

추가된 이미지.

## 비고

이 메서드는 WMF/EMF 메타파일을 래스터 PNG 이미지로 변환하지 않고도 프레젠테이션에 추가할 수 있습니다.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) 메서드

스트림에서 이미지를 생성하고 프레젠테이션에 추가합니다.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 이미지 파일을 추가할 스트림. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | 스트림에 적용될 동작. |

### 반환 값

추가된 [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) 메서드

지정된 버퍼에서 프레젠테이션에 이미지를 추가합니다.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 버퍼. |

### 반환 값

추가된 이미지.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) 메서드

다른 프레젠테이션에서 이미지 사본을 추가합니다.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | 원본 이미지. |

### 반환 값

추가된 이미지.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) 메서드

SVG 객체에서 프레젠테이션에 이미지를 추가합니다.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG 이미지 객체 [ISvgImage](../../isvgimage/) |

### 반환 값

추가된 이미지.

## 관련 항목

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)