---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API リファレンス
description: ブラシのレンダリングに ROP 操作または不透明度を使用します。
type: docs
weight: 27
url: /ja/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() メソッド

ブラシのレンダリングに ROP 操作または Opacity を使用します。

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## 備考

デフォルト値は true です。

次の例は、[Ink](../../../aspose.slides.ink/) 要素のエクスポートに ROP を使用して設定する方法を示しています：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 関連項目

* クラス [InkOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)