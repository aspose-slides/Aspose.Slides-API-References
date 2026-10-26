---
title: set_AccessPermissions()
second_title: Aspose.Slides for C++ API リファレンス
description: ユーザーアクセスで文書が開かれたときに付与すべきアクセス許可を指定するフラグの集合を含みます。PdfAccessPermissions を参照してください。
type: docs
weight: 313
url: /ja/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) メソッド


ユーザーアクセスで文書が開かれたときに付与されるべきアクセス権限を指定するフラグの集合を含みます。参照 [PdfAccessPermissions](../../pdfaccesspermissions/)。

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
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

* Enum [PdfAccessPermissions](../../pdfaccesspermissions/)
* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)