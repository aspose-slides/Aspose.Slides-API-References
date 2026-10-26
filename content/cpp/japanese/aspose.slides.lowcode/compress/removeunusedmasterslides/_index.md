---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides for C++ API リファレンス
description: 未使用のマスタースライドを削除して Presentation を圧縮します。
type: docs
weight: 1
url: /ja/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) メソッド


未使用のマスタースライドを削除して [Presentation](../../../aspose.slides/presentation/) を圧縮します。

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | プレゼンテーション インスタンス |
## 備考




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [Compress](../)
* 名前空間 [Aspose::Slides::LowCode](../../)
* ライブラリ [Aspose.Slides](../../../)