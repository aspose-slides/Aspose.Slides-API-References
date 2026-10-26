---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides for C++ API 參考文件
description: 透過移除嵌入式字型中未使用的字元來壓縮簡報。
type: docs
weight: 27
url: /zh-hant/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) 方法

透過移除嵌入式字型中未使用的字元來壓縮 [Presentation](../../../aspose.slides/presentation/)。

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 簡報實例 |
## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [Compress](../)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)