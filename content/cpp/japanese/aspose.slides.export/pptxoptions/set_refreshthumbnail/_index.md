---
title: set_RefreshThumbnail()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのサムネイルが更新されるかどうかを指定します。boolを書き込みます。デフォルト値はtrueです。
type: docs
weight: 66
url: /ja/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) メソッド

プレゼンテーションのサムネイルが更新されるかどうかを指定します。**bool**を書き込みます。デフォルト値は**true**です。

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
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

* クラス [PptxOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)