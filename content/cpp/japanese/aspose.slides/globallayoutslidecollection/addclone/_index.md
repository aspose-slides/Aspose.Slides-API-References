---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたレイアウトスライドのコピーをプレゼンテーションに追加します。
type: docs
weight: 1
url: /ja/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) メソッド

指定されたレイアウトスライドのコピーをプレゼンテーションに追加します。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) をクローンします。 |

### 戻り値

追加されたスライド。

## 備考

異なるプレゼンテーション間でレイアウトをクローンする際、元の書式設定を保持するためにレイアウトのマスターもクローンされることがあります。内部レジストリは自動的にクローンされたマスターを追跡し、同じマスタースライドのクローンが複数作成されるのを防止します。マスタースライドの手動クローンは防止も登録もされません。

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) メソッド

指定されたレイアウトスライドのコピーをプレゼンテーションに追加します。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) をクローンします。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新しいレイアウト用のマスタースライド。 |

### 戻り値

追加されたスライド。

## 備考

1) 新しいレイアウトは宛先プレゼンテーションで定義されたマスターにリンクされます。したがって、これは PowerPoint の「Use Destination Theme」オプションを使用したコピー/貼り付けに相当します。 2) このメソッドに相当するものは、[IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) メソッドで、[IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) プロパティからアクセスできます。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [GlobalLayoutSlideCollection](../)
* クラス [IMasterSlide](../../imasterslide/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)