---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API リファレンス
description: ブラシの描画に ROP 操作または不透明度を使用します。
type: docs
weight: 40
url: /ja/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) メソッド


ブラシの描画に ROP 操作または不透明度を使用します。

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## 備考


既定値は true です。 

次の例は、[Ink](../../../aspose.slides.ink/) 要素のエクスポートに ROP を使用して設定する方法を示しています: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 参照

* クラス [IInkOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)