---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides for C++ API リファレンス
description: 事前に作成された列挙子をラップし、すべての呼び出しをそれにリダイレクトするイテレータです。
type: docs
weight: 196
url: /ja/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator クラス

事前に作成された列挙子をラップし、すべての呼び出しをそれにリダイレクトするイテレータです。

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Element | Element 型。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | 現在のイテレータをクローンします。 |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | イテレータを1ステップ前進させます。m_is_end と m_pointer を更新する必要があります。 |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | 2つのイテレータが同じアイテムを指しているか確認します。 |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | デストラクタ。 |

## 参照

* 名前空間 [System::Collections::Generic](../)
* ライブラリ [Aspose.Slides](../../)