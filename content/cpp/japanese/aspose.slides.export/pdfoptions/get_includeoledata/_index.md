---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API リファレンス
description: True は、プレゼンテーションからすべての OLE データを変換し、生成された PDF に埋め込みファイルとして保存します。bool を読み取ります。
type: docs
weight: 456
url: /ja/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() メソッド

True は、プレゼンテーションからすべての OLE データを変換し、生成された PDF に埋め込みファイルとして保存します。読み取り **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## 備考

デフォルトは **false** です。 

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 参照

* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)