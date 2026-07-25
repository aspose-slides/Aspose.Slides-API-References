---
title: get_DetectTables()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: PDF ファイルをインポートする際にテーブルを検出するかどうかを決定します。
type: docs
weight: 1
url: /ja/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const メソッド

pdf ファイルをインポートする際にテーブルを検出するかどうかを決定します。

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
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