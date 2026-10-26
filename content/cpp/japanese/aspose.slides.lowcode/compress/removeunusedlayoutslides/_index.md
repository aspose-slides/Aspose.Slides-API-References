---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides for C++ API リファレンス
description: 未使用のレイアウトスライドを削除することで、Presentation の圧縮を行います。
type: docs
weight: 14
url: /ja/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) メソッド


未使用のレイアウトスライドを削除することで、[Presentation](../../../aspose.slides/presentation/) の圧縮を行います。

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | プレゼンテーション インスタンス |
## 備考


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [Compress](../)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)