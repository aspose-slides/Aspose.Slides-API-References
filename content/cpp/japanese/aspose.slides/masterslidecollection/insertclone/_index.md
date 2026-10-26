---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたマスタースライドのコピーをコレクションの指定された位置に挿入します。リンクされたレイアウトスライドもコピーされます。
type: docs
weight: 105
url: /ja/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) メソッド

指定されたマスタースライドのコピーをコレクションの指定された位置に挿入します。リンクされたレイアウトスライドもコピーされます。

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) をクローンします。 |

### 戻り値

挿入されたマスタースライド。

## 備考

次の例は、別の PowerPoint [Presentation](../../presentation/) でマスタースライドをクローンする方法を示しています。
```cpp
// ソースプレゼンテーションファイルを読み込むために Presentation クラスのインスタンスを作成します
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// スライドがクローンされる宛先プレゼンテーション用に Presentation クラスのインスタンスを作成します
auto destPres = System::MakeObject<Presentation>();

// ソースプレゼンテーションのスライドコレクションから ISlide をインスタンス化し、
// マスタースライドも取得します
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// 宛先プレゼンテーションのマスタースライドを取得します
auto masters = destPres->get_Masters();
// ソースプレゼンテーションから目的のマスタースライドを、
// 宛先プレゼンテーションのマスターコレクションへクローンします
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// 宛先プレゼンテーションのスライドコレクション
auto slides = destPres->get_Slides();
// ソーススライドを宛先のスライドコレクションにクローンします。
slides->AddClone(sourceSlide, iSlide, true);
// 宛先プレゼンテーションをディスクに保存します
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMasterSlide](../../imasterslide/)
* クラス [MasterSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)