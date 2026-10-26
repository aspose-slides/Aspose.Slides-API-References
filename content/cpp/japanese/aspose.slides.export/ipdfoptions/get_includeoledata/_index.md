---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API リファレンス
description: True は、プレゼンテーションからすべての OLE データを、生成された PDF の埋め込みファイルに変換します。bool を読み取ります。
type: docs
weight: 456
url: /ja/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() メソッド

True は、プレゼンテーションからすべての OLE データを、生成された PDF の埋め込みファイルに変換します。読み取り **bool**。

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
```

## 備考

デフォルトは **false** です。  

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## 参照

* クラス [IPdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)