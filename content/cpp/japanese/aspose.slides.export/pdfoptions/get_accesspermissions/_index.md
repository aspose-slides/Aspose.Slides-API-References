---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ API リファレンス
description: ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス許可を指定するフラグのセットを含みます。PdfAccessPermissions を参照してください。
type: docs
weight: 300
url: /ja/aspose.slides.export/pdfoptions/get_accesspermissions/
---
## PdfOptions::get_AccessPermissions() メソッド


ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス許可を指定するフラグのセットを含みます。[PdfAccessPermissions](../../pdfaccesspermissions/) を参照してください。

```cpp
PdfAccessPermissions Aspose::Slides::Export::PdfOptions::get_AccessPermissions() override
```

## 備考


```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## 関連項目

* 列挙体 [PdfAccessPermissions](../../pdfaccesspermissions/)
* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)