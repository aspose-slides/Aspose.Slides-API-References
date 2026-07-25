---
title: set_AccessPermissions()
second_title: Aspose.Slides for C++ API リファレンス
description: ドキュメントがユーザーアクセスで開かれたときに付与されるべきアクセス許可を指定するフラグのセットを含みます。PdfAccessPermissions を参照してください。
type: docs
weight: 274
url: /ja/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) メソッド


ドキュメントがユーザーアクセスで開かれたときに付与されるべきアクセス許可を指定するフラグのセットを含みます。[PdfAccessPermissions](../../pdfaccesspermissions/)を参照してください。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## 備考



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## 参照

* 列挙型 [PdfAccessPermissions](../../pdfaccesspermissions/)
* クラス [IPdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)