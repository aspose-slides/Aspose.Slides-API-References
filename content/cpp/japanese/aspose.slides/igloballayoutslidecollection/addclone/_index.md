---
title: AddClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。
type: docs
weight: 1
url: /ja/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) メソッド


指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) をクローンします。 |

### Return Value

追加されたスライド。

## 備考



異なるプレゼンテーション間でレイアウトをクローンする場合、レイアウトのマスターもクローンされ、元の書式設定が保持されます。内部レジストリは自動的にクローンされたマスターを追跡し、同一マスタースライドの複数クローン作成を防止します。マスタースライドの手動クローンは防止も登録もされません。 
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) メソッド


指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) をクローンします。 |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 新しいレイアウトのためのマスタースライド。 |

### Return Value

追加されたスライド。

## 備考



新しいレイアウトは宛先プレゼンテーションで定義されたマスターにリンクされます。したがって、PowerPoint の「Use Destination Theme」オプションを使用したコピー/貼り付けと同等です。 
## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [IGlobalLayoutSlideCollection](../)
* クラス [IMasterSlide](../../imasterslide/)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)