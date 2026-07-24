---
title: ObjectToUnknown()
second_title: Aspose.Slides for C++ API Referansı
description: Object'i bilinmeyen bir tipe dönüştürür, hem akıllı işaretçi tipini hem de bpxed değer durumlarını işler.
type: docs
weight: 131
url: /tr/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) yöntemi


[Object](../../object/)'yi bilinmeyen bir tipe dönüştürür, hem akıllı işaretçi türünü hem de bpxed değer durumlarını ele alır.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../object/)'yi dönüştürmek için tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/)'yi dönüştürmek. |

### Dönüş Değeri

Ya kutusu açılmış değer ya da dönüştürülmüş işaretçi.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) yöntemi


[Object](../../object/)'yi bilinmeyen bir tipe dönüştürür, hem akıllı işaretçi türünü hem de boxed değer durumlarını ele alır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../object/)'yi dönüştürmek için tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/)'yi dönüştürmek. |

### Dönüş Değeri

Ya kutusu açılmış değer ya da dönüştürülmüş işaretçi.

## Ayrıca Bakınız

* Sınıf [SmartPtr](../../smartptr/)
* Sınıf [Object](../../object/)
* Sınıf [ObjectExt](../)
* Yapı [IsSmartPtr](../../issmartptr/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)