---
title: operator=()
second_title: Aspose.Slides for C++ API Referansı
description: SmartPtr nesnesine taşıma ataması yapar. x kullanılamaz hale gelir.
type: docs
weight: 27
url: /tr/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) metodu

[SmartPtr](../) nesnesine taşıma ataması yapar. x kullanılamaz hale gelir.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move-assign. |

### Dönüş Değeri

Reference to this object.

## SmartPtr::operator=(const SmartPtr_&) metodu

[SmartPtr](../) nesnesine kopya atama yapar.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Pointer to copy-assign. |

### Dönüş Değeri

Reference to this object.

## SmartPtr::operator=(const SmartPtr\<Q\>&) metodu

[SmartPtr](../) nesnesine kopya atama yapar. Gerekli tip dönüşümlerini gerçekleştirir.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | x tarafından işaret edilen nesnenin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer to copy-assign. |

### Dönüş Değeri

Reference to this object.

## SmartPtr::operator=(Pointee_ *) metodu

Ham işaretçiyi [SmartPtr](../) nesnesine atar.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Atanacak işaretçi değeri. |

### Dönüş Değeri

Reference to this object.

## SmartPtr::operator=(std::nullptr_t) metodu

İşaretçi değerini nullptr olarak ayarlar.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### Dönüş Değeri

Reference to this object.

## İlgili

* Tip Tanımı [SmartPtr_](../smartptr_/)
* Tip Tanımı [Pointee_](../pointee_/)
* Sınıf [SmartPtr](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)