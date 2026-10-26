---
title: ToSvg()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتحويل Presentation إلى SVG.
type: docs
weight: 27
url: /ar/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) طريقة

يقوم بتحويل [Presentation](../../../aspose.slides/presentation/) إلى SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | مسار العرض التقديمي المدخل |
## ملاحظات

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) طريقة

يقوم بتحويل [Presentation](../../../aspose.slides/presentation/) إلى SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | مسار العرض التقديمي المدخل |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | دالة رد الاتصال التي تُعيد مسار الإخراج SVG لكل شريحة في العرض التقديمي |
## ملاحظات

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) طريقة

يقوم بتحويل [Presentation](../../../aspose.slides/presentation/) إلى SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | دالة رد الاتصال التي تُعيد مسار الإخراج SVG لكل شريحة في العرض التقديمي |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) طريقة

يقوم بتحويل [Presentation](../../../aspose.slides/presentation/) إلى SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | خيارات تصدير SVG |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) طريقة

يقوم بتحويل [Presentation](../../../aspose.slides/presentation/) إلى SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | دالة رد الاتصال التي تُعيد مسار الإخراج SVG لكل شريحة في العرض التقديمي |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | خيارات تصدير SVG |
## ملاحظات

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

## انظر أيضًا

* تعريف نوع [GetOutPathCallback](../getoutpathcallback/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [Convert](../)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* مساحة الاسم [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)