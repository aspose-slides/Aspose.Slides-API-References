---
title: ToSvg()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แปลง Presentation เป็น SVG.
type: docs
weight: 27
url: /th/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) method


แปลง [Presentation](../../../aspose.slides/presentation/) เป็น SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | เส้นทางของงานนำเสนอที่รับเข้า |
## หมายเหตุ




```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) method


แปลง [Presentation](../../../aspose.slides/presentation/) เป็น SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | เส้นทางของงานนำเสนอที่รับเข้า |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | คอลแบ็กที่คืนค่าเส้นทางเอาต์พุต SVG สำหรับแต่ละสไลด์ในงานนำเสนอ |
## หมายเหตุ




```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) method


แปลง [Presentation](../../../aspose.slides/presentation/) เป็น SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | งานนำเสนอที่รับเข้า |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | คอลแบ็กที่คืนค่าเส้นทางเอาต์พุต SVG สำหรับแต่ละสไลด์ในงานนำเสนอ |
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) method


แปลง [Presentation](../../../aspose.slides/presentation/) เป็น SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | งานนำเสนอที่รับเข้า |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | ตัวเลือกการส่งออก SVG |
## หมายเหตุ




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) method


แปลง [Presentation](../../../aspose.slides/presentation/) เป็น SVG.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | งานนำเสนอที่รับเข้า |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | คอลแบ็กที่คืนค่าเส้นทางเอาต์พุต SVG สำหรับแต่ละสไลด์ในงานนำเสนอ |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | ตัวเลือกการส่งออก SVG |
## หมายเหตุ




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

## ดูเพิ่มเติม

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)