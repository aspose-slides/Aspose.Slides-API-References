---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたレイアウトスライドのコピーをコレクションの指定位置に挿入します。
type: docs
weight: 14
url: /ja/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) メソッド

指定されたレイアウトスライドのコピーをコレクションの指定位置に挿入します。

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) のクローン。 |

### 戻り値

挿入されたスライド。

## 備考

新しいレイアウトは、このレイアウトスライドコレクションの親マスタースライドにリンクされます。したがって、PowerPoint の\"Use Destination Theme\" オプションを用いたコピー/貼り付けと同等です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ILayoutSlide](../../ilayoutslide/)
* クラス [MasterLayoutSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)