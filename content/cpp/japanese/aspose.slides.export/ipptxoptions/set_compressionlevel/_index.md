---
title: set_CompressionLevel()
second_title: Aspose.Slides for C++ API リファレンス
description: "プレゼンテーション ドキュメントを保存するときに使用される圧縮レベルを指定します。デフォルト値は CompressionLevel::Level6 です。"
type: docs
weight: 92
url: /ja/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) メソッド

プレゼンテーション ドキュメントを保存するときに使用される圧縮レベルを指定します。デフォルト値は [CompressionLevel::Level6](../../compressionlevel/) です。

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## 備考

圧縮レベルが高いほどファイルは小さくなりますが、処理時間が長くなります。実際の圧縮率はプレゼンテーションの内容に依存します。

例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 参照

* 列挙型 [CompressionLevel](../../compressionlevel/)
* クラス [IPptxOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)