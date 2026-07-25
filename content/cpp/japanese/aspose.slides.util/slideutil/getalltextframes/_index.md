---
title: GetAllTextFrames()
second_title: Aspose.Slides for C++ API リファレンス
description: PPTX プレゼンテーション内のすべてのテキスト フレームを返します。
type: docs
weight: 79
url: /ja/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) メソッド

PPTX プレゼンテーション内のすべてのテキスト フレームを返します。

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | スキャンされたプレゼンテーション。 |
| withMasters | **bool** | マスタースライドをスキャンするかどうかを決定します。 |

### 戻り値

[TextFrame](../../../aspose.slides/textframe/) オブジェクトの配列。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ITextFrame](../../../aspose.slides/itextframe/)
* クラス [IPresentation](../../../aspose.slides/ipresentation/)
* クラス [SlideUtil](../)
* 名前空間 [Aspose::Slides::Util](../../)
* ライブラリ [Aspose.Slides](../../../)