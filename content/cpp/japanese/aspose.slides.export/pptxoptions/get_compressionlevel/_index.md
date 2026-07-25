---
title: get_CompressionLevel()
second_title: Aspose.Slides for C++ API リファレンス
description: "プレゼンテーション ドキュメントを保存するときに使用される圧縮レベルを指定します。デフォルト値は CompressionLevel::Level6 です。"
type: docs
weight: 79
url: /ja/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() メソッド


プレゼンテーション ドキュメントを保存するときに使用される圧縮レベルを指定します。デフォルト値は [CompressionLevel::Level6](../../compressionlevel/) です。

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## 備考


圧縮レベルが高いほど、ファイルは小さくなりますが、処理時間が長くかかります。実際の圧縮率はプレゼンテーションの内容に依存します。 

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 参照

* Enum [CompressionLevel](../../compressionlevel/)
* クラス [PptxOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)