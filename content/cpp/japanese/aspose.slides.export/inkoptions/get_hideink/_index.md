---
title: get_HideInk()
second_title: Aspose.Slides for C++ API リファレンス
description: エクスポートされたドキュメントの Ink 要素を表示または非表示にします。
type: docs
weight: 1
url: /ja/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() メソッド

エクスポートされたドキュメントで [Ink](../../../aspose.slides.ink/) 要素を表示または非表示にします。

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## 備考

デフォルト値は false です。

次の例は、エクスポートされた PDF ドキュメントで [Ink](../../../aspose.slides.ink/) 要素を非表示にする方法を示します：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 参照

* クラス [InkOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)