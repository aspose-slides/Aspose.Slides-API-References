---
title: Contains()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションに特定の値が含まれているかどうかを判定します。
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) メソッド


コレクションに特定の値が含まれているかどうかを判定します。

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | コレクション内で検索するオブジェクト。 |

### 戻り値

コレクション内に *item* が見つかった場合は true、見つからない場合は false を返します。
## 備考



例: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)