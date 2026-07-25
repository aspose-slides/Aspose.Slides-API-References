---
title: set_DetectTables()
second_title: Aspose.Slides for C++ API リファレンス
description: PDF ファイルをインポートする際にテーブルを検出するかどうかを決定します。
type: docs
weight: 14
url: /ja/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) メソッド


PDF ファイルをインポートする際にテーブルを検出するかどうかを決定します。

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [PdfImportOptions](../)
* 名前空間 [Aspose::Slides::Import](../../)
* ライブラリ [Aspose.Slides](../../../)