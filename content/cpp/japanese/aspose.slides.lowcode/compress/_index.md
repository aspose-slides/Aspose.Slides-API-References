---
title: Compress
second_title: Aspose.Slides for C++ API リファレンス
description: Presentation を圧縮することを目的としたメソッドのグループを表します。
type: docs
weight: 14
url: /ja/aspose.slides.lowcode/compress/
---
## Compress クラス

Represents a group of methods intended to compress [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 埋め込みフォントから未使用の文字を削除することで [Presentation](../../aspose.slides/presentation/) の圧縮を行います。 |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 未使用のレイアウトスライドを削除することで [Presentation](../../aspose.slides/presentation/) の圧縮を行います。 |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 未使用のマスタースライドを削除することで [Presentation](../../aspose.slides/presentation/) の圧縮を行います。 |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 参照

* 名前空間 [Aspose::Slides::LowCode](../)
* ライブラリ [Aspose.Slides](../../)