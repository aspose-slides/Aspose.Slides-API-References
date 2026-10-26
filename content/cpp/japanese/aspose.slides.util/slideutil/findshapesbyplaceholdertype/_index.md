---
title: FindShapesByPlaceholderType()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたスライド上で、指定されたプレースホルダータイプに一致するすべてのシェイプを検索します。
type: docs
weight: 14
url: /ja/aspose.slides.util/slideutil/findshapesbyplaceholdertype/
---
## SlideUtil::FindShapesByPlaceholderType(System::SharedPtr\<IBaseSlide\>, PlaceholderType) メソッド

指定されたスライド上で、指定されたプレースホルダータイプに一致するすべてのシェイプを検索します。

```cpp
static System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::Util::SlideUtil::FindShapesByPlaceholderType(System::SharedPtr<IBaseSlide> slide, PlaceholderType placeholderType)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | シェイプを検索する対象のスライド。 |
| placeholderType | [PlaceholderType](../../../aspose.slides/placeholdertype/) | シェイプをフィルタリングするプレースホルダータイプ。 |

### 戻り値

指定されたプレースホルダータイプに一致する [IShape](../../../aspose.slides/ishape/) オブジェクトの配列。

## 参照

* 列挙体 [PlaceholderType](../../../aspose.slides/placeholdertype/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../../aspose.slides/ishape/)
* クラス [IBaseSlide](../../../aspose.slides/ibaseslide/)
* クラス [SlideUtil](../)
* 名前空間 [Aspose::Slides::Util](../../)
* ライブラリ [Aspose.Slides](../../../)