---
title: ToSvg()
second_title: مرجع API Aspose.Slides برای C++
description: Presentation را به SVG تبدیل می‌کند.
type: docs
weight: 27
url: /fa/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) متد


[Presentation](../../../aspose.slides/presentation/) را به SVG تبدیل می‌کند.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | مسیر ارائه ورودی |
## توضیحات


```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) متد


[Presentation](../../../aspose.slides/presentation/) را به SVG تبدیل می‌کند.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | مسیر ارائه ورودی |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback که مسیر خروجی SVG را برای هر اسلاید در ارائه بازمی‌گرداند |
## توضیحات


```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) متد


[Presentation](../../../aspose.slides/presentation/) را به SVG تبدیل می‌کند.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Callback که مسیر خروجی SVG را برای هر اسلاید در ارائه بازمی‌گرداند |
## توضیحات


```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) متد


[Presentation](../../../aspose.slides/presentation/) را به SVG تبدیل می‌کند.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | گزینه‌های خروجی SVG |
## توضیحات


```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) متد


[Presentation](../../../aspose.slides/presentation/) را به SVG تبدیل می‌کند.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | ارائه ورودی |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Callback که مسیر خروجی SVG را برای هر اسلاید در ارائه بازمی‌گرداند |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | گزینه‌های خروجی SVG |
## توضیحات


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

## موارد مرتبط

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)