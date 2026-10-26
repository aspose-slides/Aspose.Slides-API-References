---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたスライドのコピーをコレクションの末尾に追加します。
type: docs
weight: 14
url: /ja/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) メソッド


指定されたスライドのコピーをコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンするスライド。 |

### 戻り値

新しいスライド。

## 備考



異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされることがあります。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスター スライドの複数クローンの作成を防止します。マスタースライドの手動クローンは防止も登録もされません。クローン処理をより細かく制御したい場合は、スライドのクローンに [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) または [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./)、レイアウトのクローンに [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) または [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/)、マスターのクローンに [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) を使用してください。 
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) メソッド


指定されたスライドのコピーを指定されたセクションの末尾に追加します。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンするスライド。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | 新しいスライドのための [Section](../../section/)。 |

### 戻り値

新しいスライド。

## 備考



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// 今、第二セクションには最初のスライドのコピーが含まれています。
```


## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) メソッド


指定されたスライドのコピーをコレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンするスライド。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 新しいスライドのレイアウトスライド。 |

### 戻り値

新しいスライド。

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) メソッド


指定されたソーススライドのコピーをコレクションの末尾に追加します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトとは、ソーススライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、ソーススライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）。allowCloneMissingLayout が false の場合は PptxEditException がスローされます。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンするスライド。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新しいスライドのマスタースライド。 |
| allowCloneMissingLayout | **bool** | 指定されたマスターに適切なレイアウトがない場合、ソーススライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）。allowCloneMissingLayout が false の場合は PptxEditException がスローされます。 |

### 戻り値

新しいスライド。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISlide](../../islide/)
* クラス [ISlideCollection](../)
* クラス [ISection](../../isection/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [IMasterSlide](../../imasterslide/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)