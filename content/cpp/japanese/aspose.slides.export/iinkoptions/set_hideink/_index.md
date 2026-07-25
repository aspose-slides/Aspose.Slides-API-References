---
title: set_HideInk()
second_title: Aspose.Slides for C++ API リファレンス
description: エクスポートされたドキュメント内の Ink 要素を表示または非表示にします。
type: docs
weight: 14
url: /ja/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) メソッド


エクスポートされたドキュメント内の[Ink](../../../aspose.slides.ink/)要素を表示または非表示にします。

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## 備考


デフォルト値は false です。 

次の例は、エクスポートされた PDF ドキュメント内の[Ink](../../../aspose.slides.ink/)要素を非表示にする方法を示します： 
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