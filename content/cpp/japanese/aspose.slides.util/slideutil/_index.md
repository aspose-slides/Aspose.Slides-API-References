---
title: SlideUtil
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション内のシェイプやテキストの検索を支援するメソッドを提供します。
type: docs
weight: 14
url: /ja/aspose.slides.util/slideutil/
---
## SlideUtil クラス

Offer methods which help to search shapes and text in a presentation.

```cpp
class SlideUtil
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | スライド上のすべてのシェイプの配置を変更します。シェイプを余白またはスライドの端に揃えるか、互いに相対的に揃えます。 |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | 選択されたシェイプの配置を変更します。シェイプを余白またはスライドの端に揃えるか、互いに相対的に揃えます。 |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | グループシェイプ内のすべてのシェイプの配置を変更します。シェイプを余白またはスライドの端に揃えるか、互いに相対的に揃えます。 |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | グループシェイプ内の選択されたシェイプの配置を変更します。シェイプを余白またはスライドの端に揃えるか、互いに相対的に揃えます。 |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | プレゼンテーション内のテキストを検索し、指定された形式で置換します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | PPTX プレゼンテーションで代替テキストによりシェイプを検索します。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | PPTX プレゼンテーションのスライド上で代替テキストによりシェイプを検索します。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | 指定されたスライド上で、与えられたプレースホルダータイプに一致するすべてのシェイプを検索します。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | PPTX プレゼンテーションのスライド上のすべてのテキストフレームを返します。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | PPTX プレゼンテーション内のすべてのテキストフレームを返します。 |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | 指定されたスライド上で、与えられたテキストを含むすべてのテキストフレームを返します。 |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | ソースファイル形式を対応する [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) に変換します。 |
## 参照

* 名前空間 [Aspose::Slides::Util](../)
* ライブラリ [Aspose.Slides](../../)