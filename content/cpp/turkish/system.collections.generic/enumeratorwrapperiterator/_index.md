---
title: EnumeratorWrapperIterator
second_title: Aspose.Slides for C++ API Referansı
description: Önceden oluşturulmuş enumeratörü saran ve tüm çağrıları ona yönlendiren yineleyici.
type: docs
weight: 196
url: /tr/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator sınıf

Önceden oluşturulmuş enumeratörü saran ve tüm çağrıları ona yönlendiren yineleyici.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Element | Element türü. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Geçerli yineleyiciyi kopyalar. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Yineleyiciyi bir adım ileri hareket ettirir. m_is_end ve m_pointer güncellenmelidir. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | İki yineleyicinin aynı öğeye işaret edip etmediğini denetler. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Yıkıcı. |

## Ayrıca Bakınız

* İsim Uzayı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)