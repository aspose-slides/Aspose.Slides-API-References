---
title: set_RefreshThumbnail()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのサムネイルを更新するかどうかを指定します。書き込みは bool。既定値は true です。
type: docs
weight: 66
url: /ja/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) メソッド


プレゼンテーションのサムネイルを更新するかどうかを指定します。書き込みは **bool**。デフォルト値は **true** です。

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## 備考


オプションの値が **true** の場合、新しいサムネイルが生成されます。

オプションの値が **false** の場合、現在のサムネイルはそのまま保存されます。

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