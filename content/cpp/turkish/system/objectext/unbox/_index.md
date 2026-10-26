---
title: Unbox()
second_title: Aspose.Slides for C++ API Referansı
description: Object'e dönüştürdükten sonra değer türlerini kutudan çıkarır. Enum tipleri için uygulama.
type: docs
weight: 53
url: /tr/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) yöntemi


Değer türlerini [Object](../../object/)'e dönüştürdükten sonra kutudan çıkarır. Enum tipleri için uygulama.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Enum](../../enum/) türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) kutudan çıkarmak için. |

### Dönüş Değeri

[Enum](../../enum/) değeri.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) yöntemi


Değer türlerini [Object](../../object/)'e dönüştürdükten sonra kutudan çıkarır. Enum olmayan ve null olamayan tipler için uygulama.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) kutudan çıkarmak için. |

### Dönüş Değeri

Kutudan çıkarılmış değer.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) yöntemi


Değer türlerini [Object](../../object/)'e dönüştürdükten sonra kutudan çıkarır. Enum olmayan ve null olamayan tipler için uygulama.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) kutudan çıkarmak için. |

### Dönüş Değeri

Kutudan çıkarılmış değer.

## ObjectExt::Unbox(E) yöntemi


Enum tiplerini tamsayıya kutudan çıkarır.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tamsayı türü. |
| E | Kaynak enum türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| e | E | Kutudan çıkarılacak değer. |

### Dönüş Değeri

Enumun tamsayı temsili.

## ObjectExt::Unbox(E) yöntemi


Enum tiplerini dönüştürür.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef enum türü. |
| E | Kaynak enum türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| e | E | Kutudan çıkarılacak değer. |

### Dönüş Değeri

Dönüştürülmüş enum değeri.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) yöntemi


Metin değerlerini kutudan çıkarır.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) kutudan çıkarmak için |

### Dönüş Değeri

[String](../../string/) kutulanmış dize temsili, kutulanmış dize null ise null olabilir.

## İlgili

* Sınıf [SmartPtr](../../smartptr/)
* Sınıf [Object](../../object/)
* Sınıf [ObjectExt](../)
* Sınıf [String](../../string/)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)