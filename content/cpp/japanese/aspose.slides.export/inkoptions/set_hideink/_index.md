---
title: set_HideInk()
second_title: Aspose.Slides for C++ API リファレンス
description: エクスポートされたドキュメント内の Ink 要素を表示または非表示にします。
type: docs
weight: 14
url: /ja/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) メソッド


エクスポートされたドキュメント内の [Ink](../../../aspose.slides.ink/) 要素を表示または非表示にします。

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## 備考


デフォルト値は false です。 

次の例は、エクスポートされた PDF ドキュメントで [Ink](../../../aspose.slides.ink/) 要素を非表示にする方法を示します。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 関連項目

* クラス [InkOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)