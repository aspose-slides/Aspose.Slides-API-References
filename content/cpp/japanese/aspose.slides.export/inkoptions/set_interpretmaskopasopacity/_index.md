---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API リファレンス
description: ブラシのレンダリングに ROP 操作または不透明度を使用します。
type: docs
weight: 40
url: /ja/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) メソッド


ブラシのレンダリングに ROP 操作または不透明度を使用します。

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## 備考


デフォルト値は true です。 

次の例では、[Ink](../../../aspose.slides.ink/) 要素をエクスポートするために ROP を使用して設定する方法を示します: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 参照

* クラス [InkOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)