---
title: operator=()
second_title: Aspose.Slides için C++ API Referansı
description: Akıllı işaretçiyi taşıma ataması yapar.
type: docs
weight: 27
url: /tr/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) metodu

Taşıma atama akıllı işaretçiyi atar.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Taşıma atama değeri alınan işaretçi. |

### Dönüş Değeri

Kendi referansı.

## DynamicWeakPtr::operator=(const SmartPtr_\&) metodu

Kopya atama akıllı işaretçiyi atar.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Kopya atama değeri alınan işaretçi. |

### Dönüş Değeri

Kendi referansı.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) metodu

Kopya atama akıllı işaretçiyi atar.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | Kaynak işaretçili tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Kopya atama değeri alınan işaretçi. |

### Dönüş Değeri

Kendi referansı.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) metodu

Akıllı işaretçiyi atar.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | İşaretçi değeri. |

### Dönüş Değeri

Kendi referansı.

## DynamicWeakPtr::operator=(std::nullptr_t) metodu

Akıllı işaretçiyi null olarak ayarlar.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### Dönüş Değeri

Kendi referansı.

## Ayrıca Bakınız

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Sınıf [DynamicWeakPtr](../)
* Sınıf [SmartPtr](../../smartptr/)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)