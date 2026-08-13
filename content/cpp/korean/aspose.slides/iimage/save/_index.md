---
title: Save()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이미지를 파일에 저장합니다.
type: docs
weight: 40
url: /ko/aspose.slides/iimage/save/
---
## IImage::Save(System::String) 메서드


이미지를 파일에 저장합니다.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 이미지가 저장될 파일의 경로입니다. |

## IImage::Save(System::String, ImageFormat) 메서드


이미지를 지정된 형식으로 파일에 저장합니다.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 이미지가 저장될 파일의 경로입니다. |
| format | [ImageFormat](../../imageformat/) | 이미지 형식입니다. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) 메서드


이미지를 지정된 형식으로 스트림에 저장합니다.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 이미지가 저장될 스트림입니다. |
| format | [ImageFormat](../../imageformat/) | 이미지 형식입니다. |

## IImage::Save(System::String, ImageFormat, int32_t) 메서드


이미지를 지정된 형식과 품질로 파일에 저장합니다.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 이미지가 저장될 파일의 경로입니다. |
| format | [ImageFormat](../../imageformat/) | 이미지 형식입니다. |
| quality | **int32_t** | 저장된 이미지의 품질(0~100).  

 이 매개변수는 [ImageFormat::Jpeg](../../imageformat/) 저장에만 영향을 미칩니다. 다른 모든 형식에서는 무시됩니다. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) 메서드


이미지를 지정된 형식과 품질로 스트림에 저장합니다.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 이미지가 저장될 스트림입니다. |
| format | [ImageFormat](../../imageformat/) | 이미지 형식입니다. |
| quality | **int32_t** | 저장된 이미지의 품질(0~100).  

 이 매개변수는 [ImageFormat::Jpeg](../../imageformat/) 저장에만 영향을 미칩니다. 다른 모든 형식에서는 무시됩니다. |

## 참조

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IImage](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)