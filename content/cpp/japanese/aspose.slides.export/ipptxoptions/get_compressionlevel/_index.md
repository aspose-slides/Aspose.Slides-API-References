---
title: get_CompressionLevel()
second_title: Aspose.Slides for C++ API リファレンス
description: "プレゼンテーション ドキュメントを保存する際に使用される圧縮レベルを指定します。デフォルト値は CompressionLevel::Level6 です。"
type: docs
weight: 79
url: /ja/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() メソッド

プレゼンテーション ドキュメントを保存する際に使用される圧縮レベルを指定します。デフォルト値は [CompressionLevel::Level6](../../compressionlevel/) です。

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## 備考

圧縮レベルが高いほどファイルは小さくなりますが、処理時間が長くかかります。実際の圧縮率はプレゼンテーションの内容によって異なります。  

例:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 参考

* Enum [CompressionLevel](../../compressionlevel/)
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)