---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたスライドのコピーをコレクションの指定位置に挿入します。
type: docs
weight: 27
url: /ja/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) メソッド


指定されたスライドのコピーをコレクションの指定位置に挿入します。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンする。 |

### 戻り値

挿入されたスライド。

## 備考



異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされる可能性があります。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスター スライドの複数クローンの作成を防止します。マスター スライドの手動クローンは防止も登録もされません。クローン処理をより細かく制御したい場合は、スライドのクローンに [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) または [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) を、マスターのクローンに [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) を使用してください。 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) メソッド


指定されたスライドのコピーをコレクションの指定位置に挿入します。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンする。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 新しいスライド用のレイアウト スライド。 |

### 戻り値

挿入されたスライド。

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) メソッド


指定されたソース スライドのコピーをコレクションの指定位置に挿入します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトは、ソース スライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、ソース スライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）。allowCloneMissingLayout が false の場合は PptxEditException がスローされます。

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) をクローンする。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新しいスライド用のマスター スライド。 |
| allowCloneMissingLayout | **bool** | 指定されたマスターに適切なレイアウトがない場合、ソース スライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）。allowCloneMissingLayout が false の場合は PptxEditException がスローされます。 |

### 戻り値

挿入されたスライド。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISlide](../../islide/)
* クラス [ISlideCollection](../)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [IMasterSlide](../../imasterslide/)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)