---
title: ToSvg()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 프레젠테이션을 SVG로 변환합니다.
type: docs
weight: 27
url: /ko/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) 메서드

[Presentation](../../../aspose.slides/presentation/)를 SVG로 변환합니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 입력 프레젠테이션의 경로 |

## 비고

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) 메서드

[Presentation](../../../aspose.slides/presentation/)를 SVG로 변환합니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 입력 프레젠테이션의 경로 |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | 프레젠테이션의 각 슬라이드에 대한 SVG 출력 경로를 반환하는 콜백 |

## 비고

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) 메서드

[Presentation](../../../aspose.slides/presentation/)를 SVG로 변환합니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션 |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >프레젠테이션의 각 슬라이드에 대한 SVG 출력 경로를 반환하는 콜백 |

## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) 메서드

[Presentation](../../../aspose.slides/presentation/)를 SVG로 변환합니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG 내보내기 옵션 |

## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) 메서드

[Presentation](../../../aspose.slides/presentation/)를 SVG로 변환합니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션 |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | 프레젠테이션의 각 슬라이드에 대한 SVG 출력 경로를 반환하는 콜백 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG 내보내기 옵션 |

## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, callback, svgOptions);
```

## 참조

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Convert](../)
* 클래스 [Presentation](../../../aspose.slides/presentation/)
* 클래스 [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* 네임스페이스 [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)