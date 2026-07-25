---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides の C++ API リファレンス
description: 埋め込みフォントから未使用文字を削除して、Presentation の圧縮を行います。
type: docs
weight: 27
url: /ja/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) メソッド

埋め込みフォントから未使用の文字を削除することで、[Presentation](../../../aspose.slides/presentation/) の圧縮を行います。

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | プレゼンテーション インスタンス |
## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [Compress](../)
* 名前空間 [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)