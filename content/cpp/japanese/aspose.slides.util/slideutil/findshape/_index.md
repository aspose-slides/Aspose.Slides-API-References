---
title: FindShape()
second_title: Aspose.Slides for C++ API リファレンス
description: PPTX プレゼンテーションで代替テキストからシェイプを検索します。
type: docs
weight: 1
url: /ja/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) メソッド


PPTX プレゼンテーションで代替テキストからシェイプを検索します。

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | スキャンされたプレゼンテーション。 |
| altText | [System::String](../../../system/string/) | シェイプの代替テキスト。 |

### 戻り値

[Shape](../../../aspose.slides/shape/) または null。

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) メソッド


PPTX プレゼンテーションのスライド上で代替テキストからシェイプを検索します。

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | スキャンされたスライド。 |
| altText | [System::String](../../../system/string/) | シェイプの代替テキスト。 |

### 戻り値

[Shape](../../../aspose.slides/shape/) または null。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IShape](../../../aspose.slides/ishape/)
* クラス [IPresentation](../../../aspose.slides/ipresentation/)
* クラス [String](../../../system/string/)
* クラス [SlideUtil](../)
* クラス [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 名前空間 [Aspose::Slides::Util](../../)
* ライブラリ [Aspose.Slides](../../../)