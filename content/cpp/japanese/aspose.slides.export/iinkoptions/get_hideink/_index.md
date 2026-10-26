---
title: get_HideInk()
second_title: Aspose.Slides for C++ API リファレンス
description: エクスポートされたドキュメント内の Ink 要素を表示または非表示にします。
type: docs
weight: 1
url: /ja/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() メソッド


エクスポートされたドキュメント内の [Ink](../../../aspose.slides.ink/) 要素を表示または非表示にします。

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## 備考


デフォルト値は false です。 
次の例は、エクスポートされた PDF ドキュメント内で [Ink](../../../aspose.slides.ink/) 要素を非表示にする方法を示しています: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 参照

* クラス [IInkOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)