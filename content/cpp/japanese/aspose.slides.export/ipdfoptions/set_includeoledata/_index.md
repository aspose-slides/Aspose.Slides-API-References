---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ APIリファレンス
description: プレゼンテーションからすべての OLE データを変換し、生成された PDF に埋め込みファイルとして保存する場合は true を指定します。書き込みは bool です。
type: docs
weight: 469
url: /ja/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) メソッド


true を指定すると、プレゼンテーションからすべての OLE データを変換し、生成された PDF に埋め込みファイルとして保存します。書き込みは **bool** です。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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

## 関連項目

* クラス [IPdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)