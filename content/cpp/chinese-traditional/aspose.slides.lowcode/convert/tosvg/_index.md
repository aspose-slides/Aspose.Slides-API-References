---
title: ToSvg()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 Presentation 轉換為 SVG。
type: docs
weight: 27
url: /zh-hant/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) 方法

將 [Presentation](../../../aspose.slides/presentation/) 轉換為 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 輸入簡報的路徑 |

## 備註




```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) 方法

將 [Presentation](../../../aspose.slides/presentation/) 轉換為 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 輸入簡報的路徑 |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | 回呼，用於返回簡報中每張投影片的 SVG 輸出路徑 |

## 備註




```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) 方法

將 [Presentation](../../../aspose.slides/presentation/) 轉換為 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入簡報 |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >回呼，用於返回簡報中每張投影片的 SVG 輸出路徑 |

## 備註




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) 方法

將 [Presentation](../../../aspose.slides/presentation/) 轉換為 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入簡報 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG 匯出選項 |

## 備註




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) 方法

將 [Presentation](../../../aspose.slides/presentation/) 轉換為 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 輸入簡報 |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | 回呼，用於返回簡報中每張投影片的 SVG 輸出路徑 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG 匯出選項 |

## 備註




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

## 另請參閱

* Typedef [GetOutPathCallback](../getoutpathcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [Convert](../)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)