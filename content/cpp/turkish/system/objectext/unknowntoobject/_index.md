---
title: UnknownToObject()
second_title: Aspose.Slides for C++ API Referansı
description: Bilinmeyen türü Object'e dönüştürür, hem akıllı işaretçi türü hem de değer türü durumlarını ele alır.
type: docs
weight: 118
url: /tr/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) yöntemi

Bilinmeyen türü [Object](../../object/)'ye dönüştürür, hem akıllı işaretçi türü hem de değer türü durumlarını ele alır.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../object/)'ye dönüştürülecek tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T | [Object](../../object/)'yi dönüştürmek için. |

### Dönüş Değeri

[Object](../../object/)'ye akıllı işaretçi, dönüştürülmüş işaretçi ya da kutulanmış değer olabilir.

## ObjectExt::UnknownToObject(const T\&) yöntemi

Bilinmeyen türü [Object](../../object/)'ye dönüştürür, hem akıllı işaretçi türü hem de değer türü durumlarını ele alır.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Object](../../object/)'ye dönüştürülecek tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/)'yi dönüştürmek için. |

### Dönüş Değeri

[Object](../../object/)'ye akıllı işaretçi, dönüştürülmüş işaretçi ya da kutulanmış değer olabilir.

## Ayrıca Bakınız

* Sınıf [SmartPtr](../../smartptr/)
* Sınıf [Object](../../object/)
* Sınıf [ObjectExt](../)
* Yapı [IsSmartPtr](../../issmartptr/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)