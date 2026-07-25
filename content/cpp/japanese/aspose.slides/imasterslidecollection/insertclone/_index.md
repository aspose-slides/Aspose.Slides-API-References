---
title: InsertClone()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたマスタースライドのコピーをコレクションの指定された位置に挿入します。リンクされたレイアウトスライドもコピーされます。
type: docs
weight: 66
url: /ja/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) メソッド

指定されたマスタースライドのコピーをコレクションの指定された位置に挿入します。リンクされたレイアウトスライドもコピーされます。

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 新しいスライドのインデックス。 |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) をクローンする。 |

### 戻り値

挿入されたマスタースライド。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMasterSlide](../../imasterslide/)
* クラス [IMasterSlideCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)