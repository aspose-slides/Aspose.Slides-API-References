---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのサムネイルを更新するかどうかを指定します。読み取り bool。デフォルト値は true です。
type: docs
weight: 53
url: /ja/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() method


プレゼンテーションのサムネイルを更新するかどうかを指定します。読み取り **bool**。デフォルト値は **true** です。

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## 備考


オプションの値が **true** のとき、新しいサムネイルが生成されます。

オプションの値が **false** のとき、現在のサムネイルはそのまま保存されます。

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## 参照

* クラス [PptxOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)