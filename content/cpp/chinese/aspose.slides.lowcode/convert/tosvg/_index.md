---
title: ToSvg()
second_title: Aspose.Slides for C++ API 参考
description: 将 Presentation 转换为 SVG。
type: docs
weight: 27
url: /zh/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) 方法

将 [Presentation](../../../aspose.slides/presentation/) 转换为 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 输入演示文稿的路径 |

## 备注

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) 方法

将 [Presentation](../../../aspose.slides/presentation/) 转换为 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 输入演示文稿的路径 |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | 返回演示文稿中每张幻灯片的 SVG 输出路径的回调 |

## 备注

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) 方法

将 [Presentation](../../../aspose.slides/presentation/) 转换为 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入演示文稿 |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >返回演示文稿中每张幻灯片的 SVG 输出路径的回调 |

## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) 方法

将 [Presentation](../../../aspose.slides/presentation/) 转换为 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入演示文稿 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG 导出选项 |

## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) 方法

将 [Presentation](../../../aspose.slides/presentation/) 转换为 SVG。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 输入演示文稿 |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | 返回演示文稿中每张幻灯片的 SVG 输出路径的回调 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG 导出选项 |

## 备注

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

## 另请参阅

* 类型定义 [GetOutPathCallback](../getoutpathcallback/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Convert](../)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)