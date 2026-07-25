---
title: ToSvg()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションを SVG に変換します。
type: docs
weight: 27
url: /ja/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) メソッド

[Presentation](../../../aspose.slides/presentation/) を SVG に変換します。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 入力プレゼンテーションのパス |

## 備考

```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) メソッド

[Presentation](../../../aspose.slides/presentation/) を SVG に変換します。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 入力プレゼンテーションのパス |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | プレゼンテーション内の各スライドに対する SVG 出力パスを返すコールバック |

## 備考

```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) メソッド

[Presentation](../../../aspose.slides/presentation/) を SVG に変換します。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >プレゼンテーション内の各スライドに対する SVG 出力パスを返すコールバック |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) メソッド

[Presentation](../../../aspose.slides/presentation/) を SVG に変換します。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG エクスポートオプション |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) メソッド

[Presentation](../../../aspose.slides/presentation/) を SVG に変換します。

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 入力プレゼンテーション |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | プレゼンテーション内の各スライドに対する SVG 出力パスを返すコールバック |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG エクスポートオプション |

## 備考

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

## 参照

* 型定義 [GetOutPathCallback](../getoutpathcallback/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Convert](../)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)