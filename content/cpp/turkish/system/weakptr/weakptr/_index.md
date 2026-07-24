---
title: WeakPtr()
second_title: Aspose.Slides for C++ API Referansı
description: Null işaretçi oluşturur.
type: docs
weight: 1
url: /tr/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) yapıcı

Null işaretçi oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) yapıcı

Verilen nesneye zayıf işaretçi oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) zayıf işaretçi oluşturmak için. |

## WeakPtr::WeakPtr(const SmartPtr_&) yapıcı

ptr işaret ettiği aynı işaretçiyi referans alan zayıf işaretçi oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Kopyalanacak işaretçi değerini almak için işaretçi. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) yapıcı

x işaret ettiği aynı işaretçiyi referans alan zayıf işaretçi oluşturur.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | Kaynak işaretçinin işaretçi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Kopyalanacak işaretçi değerini almak için işaretçi. |

## WeakPtr::WeakPtr(const WeakPtr_&) yapıcı

Zayıf işaretçiyi kopya yapıcı ile oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Kopyalanacak işaretçi değerini almak için işaretçi. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) yapıcı

Zayıf işaretçiyi kopya yapıcı ile oluşturur.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | Kaynak işaretçi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Kopyalanacak işaretçi değerini almak için işaretçi. |

## WeakPtr::WeakPtr(SmartPtr_&&) yapıcı

Zayıf işaretçiyi taşıma yapıcı ile oluşturur.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Taşınacak işaretçi değerini almak için işaretçi. |

## İlgili

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Sınıf [WeakPtr](../)
* Sınıf [SmartPtr](../../smartptr/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)