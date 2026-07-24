---
title: DynamicWeakPtr()
second_title: Aspose.Slides için C++ API Referansı
description: Null akıllı işaretçi oluşturur.
type: docs
weight: 1
url: /tr/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) yapıcı

Null akıllı işaretçi oluşturur.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) yapıcı

Verilen nesneye işaret eden akıllı işaretçi oluşturur.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Pointee. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) yapıcı

Akıllı işaretçiyi kopya yapıcı ile oluşturur.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Kopyalanacak işaretçi bilgisini içeren akıllı işaretçi. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) yapıcı

Akıllı işaretçiyi kopya yapıcı ile oluşturur.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | Kaynak gösterici işaretçi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Kopyalanacak işaretçi bilgisini içeren akıllı işaretçi. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) yapıcı

Akıllı işaretçiyi kopya yapıcı ile oluşturur.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Kopyalanacak işaretçi bilgisini içeren akıllı işaretçi. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) yapıcı

Akıllı işaretçiyi taşıma yapıcı ile oluşturur.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Taşınacak işaretçi bilgisini içeren akıllı işaretçi. Çağrıdan sonra kullanılamaz hale gelir. |

## Ayrıca bakınız

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Sınıf [DynamicWeakPtr](../)
* Sınıf [SmartPtr](../../smartptr/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)