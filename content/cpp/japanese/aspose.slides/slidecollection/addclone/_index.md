---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたスライドのコピーをコレクションの末尾に追加します。
type: docs
weight: 53
url: /ja/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) メソッド

指定されたスライドのコピーをコレクションの末尾に追加します。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) のクローン対象。 |

### 戻り値

新しいスライド。

## 備考

異なるプレゼンテーション間でスライドをクローンする場合、スライドのマスターもクローンされることがあります。内部レジストリは自動的にクローンされたマスターを追跡し、同一のマスタースライドのクローンが複数作成されるのを防止します。マスタースライドの手動クローンは防止も登録もされません。クローンプロセスをより細かく制御したい場合は、スライドのクローンに [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) または [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) を、レイアウトのクローンに [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) または [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) を、マスターのクローンに [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) を使用してください。

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) メソッド

指定されたスライドのコピーを指定されたセクションの末尾に追加します。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) のクローン対象。 |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | 新しいスライド用の [Section](../../section/)。 |

### 戻り値

新しいスライド。

## 備考

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// 現在、第二セクションには最初のスライドのコピーが含まれています。
```

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) メソッド

指定されたスライドのコピーをコレクションの末尾に追加します。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) のクローン対象。 |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 新しいスライド用のレイアウトスライド。 |

### 戻り値

新しいスライド。

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) メソッド

指定されたソーススライドのコピーをコレクションの末尾に追加します。適切なレイアウトは、指定されたマスターから自動的に選択されます（適切なレイアウトとは、ソーススライドのレイアウトと同じ Type または Name を持つレイアウトです）。適切なレイアウトが存在しない場合、ソーススライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) のクローン対象。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新しいスライド用のマスタースライド。 |
| allowCloneMissingLayout | **bool** | 指定されたマスターに適切なレイアウトがない場合、ソーススライドのレイアウトがクローンされます（allowCloneMissingLayout が true の場合）または PptxEditException がスローされます（allowCloneMissingLayout が false の場合）。 |

### 戻り値

新しいスライド。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ISection](../../isection/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)