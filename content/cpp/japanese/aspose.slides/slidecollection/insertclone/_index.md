---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたスライドのコピーをコレクションの指定位置に挿入します。
type: docs
weight: 66
url: /ja/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) メソッド

指定されたスライドのコピーをコレクションの指定位置に挿入します。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンします。 |

### 戻り値

挿入されたスライド。

## 備考

異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされることがあります。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスタースライドの複数のクローンが作成されるのを防止します。マスタースライドの手動クローンは防止も登録もされません。クローン処理をより細かく制御する必要がある場合は、スライドのクローンに [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) または [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) を、マスターのクローンに [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) を使用してください。

次の例は、[Presentation](../../presentation/) 内で別の位置にクローンする方法を示しています。  
```cpp
// プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// 同じプレゼンテーション内のスライドコレクションの末尾に目的のスライドをクローンします
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// 同じプレゼンテーション内の指定インデックスに目的のスライドをクローンします
slides->InsertClone(2, slides->idx_get(1));
// 変更されたプレゼンテーションをディスクに保存します
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 次の例は、[Presentation](../../presentation/) 内で別の位置にクローンする方法を示しています。  
```cpp
// ソース プレゼンテーション ファイルをロードするために Presentation クラスのインスタンスを作成します
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// スライドをクローンする先の PPTX 用に Presentation クラスのインスタンスを作成します
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// 目的のプレゼンテーションをディスクに保存します
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) メソッド

指定されたスライドのコピーをコレクションの指定位置に挿入します。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンします。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 新しいスライドのレイアウトスライド。 |

### 戻り値

挿入されたスライド。

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) メソッド

指定されたソーススライドのコピーをコレクションの指定位置に挿入します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトとは、ソーススライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、ソーススライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンします。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新しいスライドのマスタースライド。 |
| allowCloneMissingLayout | **bool** | 指定されたマスターに適切なレイアウトが存在しない場合、ソーススライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。 |

### 戻り値

挿入されたスライド。

## 参考

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISlide](../../islide/)
* クラス [SlideCollection](../)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [IMasterSlide](../../imasterslide/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)