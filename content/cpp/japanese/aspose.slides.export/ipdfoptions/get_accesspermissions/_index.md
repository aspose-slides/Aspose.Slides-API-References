---
title: get_AccessPermissions()
second_title: Aspose.Slides for C++ API リファレンス
description: ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス許可を指定するフラグのセットが含まれます。PdfAccessPermissions を参照してください。
type: docs
weight: 261
url: /ja/aspose.slides.export/ipdfoptions/get_accesspermissions/
---
## IPdfOptions::get_AccessPermissions() メソッド

ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス許可を指定するフラグのセットが含まれます。[PdfAccessPermissions](../../pdfaccesspermissions/) を参照してください。

```cpp
virtual PdfAccessPermissions Aspose::Slides::Export::IPdfOptions::get_AccessPermissions()=0
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
* クラス [IPdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)