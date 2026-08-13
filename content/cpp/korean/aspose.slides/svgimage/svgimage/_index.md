---
title: SvgImage()
second_title: Aspose.Slides for C++ API 참조
description: 새 SvgImage 객체를 생성합니다.
type: docs
weight: 53
url: /ko/aspose.slides/svgimage/svgimage/
---
## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>) 생성자

새 [SvgImage](../) 객체를 만듭니다.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg 데이터. |

## SvgImage::SvgImage(System::String) 생성자

새 [SvgImage](../) 객체를 만듭니다.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg 내용. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>) 생성자

새 [SvgImage](../) 객체를 만듭니다.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg 스트림. |

## SvgImage::SvgImage(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 생성자

새 [SvgImage](../) 객체를 만듭니다.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::ArrayPtr<uint8_t> data, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Svg 데이터. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| baseUri | [System::String](../../../system/string/) | 지정된 Svg의 기본 URI입니다. 상대 링크를 확인하는 데 사용됩니다. |

## SvgImage::SvgImage(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 생성자

새 [SvgImage](../) 객체를 만듭니다.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::String svgContent, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| svgContent | [System::String](../../../system/string/) | Svg 내용. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| baseUri | [System::String](../../../system/string/) | 지정된 Svg의 기본 URI입니다. 상대 링크를 확인하는 데 사용됩니다. |

## SvgImage::SvgImage(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 생성자

새 [SvgImage](../) 객체를 만듭니다.

```cpp
Aspose::Slides::SvgImage::SvgImage(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Import::IExternalResourceResolver> externalResResolver, System::String baseUri)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Svg 스트림. |
| externalResResolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 외부 객체를 가져오는 콜백 객체입니다. 이 매개변수가 null이면 모든 외부 객체가 무시됩니다. |
| baseUri | [System::String](../../../system/string/) | 지정된 Svg의 기본 URI입니다. 상대 링크를 확인하는 데 사용됩니다. |

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [SvgImage](../)
* 클래스 [String](../../../system/string/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)