---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのサムネイルが更新されるかどうかを指定します。bool を取得。デフォルト値は true です。
type: docs
weight: 53
url: /ja/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() メソッド

プレゼンテーションのサムネイルが更新されるかどうかを指定します。取得 **bool**。デフォルト値は **true** です。

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
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

* クラス [IPptxOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)