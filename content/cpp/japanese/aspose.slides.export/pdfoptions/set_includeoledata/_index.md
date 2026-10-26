---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションからすべてのOLEデータを変換し、結果のPDFに埋め込みファイルとして保存する場合は True を指定します。書き込みは bool。
type: docs
weight: 469
url: /ja/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) メソッド


プレゼンテーションからすべてのOLEデータを変換し、結果のPDFに埋め込みファイルとして保存する場合は true を指定します。書き込みは **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
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