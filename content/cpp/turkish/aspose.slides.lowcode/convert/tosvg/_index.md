---
title: ToSvg()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumu SVG'ye dönüştürür.
type: docs
weight: 27
url: /tr/aspose.slides.lowcode/convert/tosvg/
---
## Convert::ToSvg(System::String) metodu


[Presentation](../../../aspose.slides/presentation/)'yi SVG'ye dönüştürür.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Giriş sunumunun yolu |
## Açıklamalar




```cpp
Convert::ToSvg(u"pres.pptx");
```

## Convert::ToSvg(System::String, Convert::GetOutPathCallback) metodu


[Presentation](../../../aspose.slides/presentation/)'yi SVG'ye dönüştürür.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::String presPath, Convert::GetOutPathCallback getOutPath)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | Giriş sunumunun yolu |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Sunumdaki her slayt için SVG çıktı yolunu döndüren geri çağırma |
## Açıklamalar




```cpp
auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(u"pres.pptx", callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback) metodu


[Presentation](../../../aspose.slides/presentation/)'yi SVG'ye dönüştürür.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | >Sunumdaki her slayt için SVG çıktı yolunu döndüren geri çağırma |
## Açıklamalar 




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto callback = std::function<String(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    return String::Format(u"pres_{0}-out.svg", index);
});

Convert::ToSvg(pres, callback);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metodu


[Presentation](../../../aspose.slides/presentation/)'yi SVG'ye dönüştürür.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG dışa aktarma seçenekleri |
## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

auto svgOptions = System::MakeObject<SVGOptions>();
svgOptions->set_VectorizeText(true);

Convert::ToSvg(pres, svgOptions);
```

## Convert::ToSvg(System::SharedPtr\<Presentation\>, Convert::GetOutPathCallback, System::SharedPtr\<Aspose::Slides::Export::ISVGOptions\>) metodu


[Presentation](../../../aspose.slides/presentation/)'yi SVG'ye dönüştürür.

```cpp
static void Aspose::Slides::LowCode::Convert::ToSvg(System::SharedPtr<Presentation> pres, Convert::GetOutPathCallback getOutPath, System::SharedPtr<Aspose::Slides::Export::ISVGOptions> options)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Giriş sunumu |
| getOutPath | [Convert::GetOutPathCallback](../getoutpathcallback/) | Sunumdaki her slayt için SVG çıktı yolunu döndüren geri çağırma |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG dışa aktarma seçenekleri |
## Açıklamalar 




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

## Ayrıca Bakınız

* Tip Tanımı [GetOutPathCallback](../getoutpathcallback/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [Convert](../)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Ad Alanı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)