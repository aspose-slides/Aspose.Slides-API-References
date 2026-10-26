---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションから特定のオブジェクトの最初の出現を削除します/>。
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) メソッド

コレクションから特定のオブジェクトの最初の出現を削除します/>。

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | コレクションから削除するオブジェクト。 |

### 戻り値

true if *item*  was successfully removed from the collection; otherwise, false. This method also returns false if *item*  is not found in the original collection/>.

## 備考

例: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathBlock](../../imathblock/)
* クラス [IMathBlockCollection](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)