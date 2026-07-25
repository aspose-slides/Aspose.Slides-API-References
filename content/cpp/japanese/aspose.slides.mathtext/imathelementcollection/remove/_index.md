---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションから特定のオブジェクトの最初の出現を削除します。
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) method

コレクションから特定のオブジェクトの最初の出現を削除します。

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | コレクションから削除するオブジェクト。 |

### 戻り値

true if *item* が正常にコレクションから削除された場合は true、そうでない場合は false。このメソッドは *item* が元のコレクションに見つからない場合も false を返します。

## 備考



例: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)