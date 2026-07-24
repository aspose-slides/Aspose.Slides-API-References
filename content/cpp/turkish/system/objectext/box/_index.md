---
title: Box()
second_title: Aspose.Slides için C++ API Referansı
description: Değer tiplerini Object'e dönüştürmek için kutular. Enum tipleri için uygulama.
type: docs
weight: 40
url: /tr/system/objectext/box/
---
## ObjectExt::Box(const T\&) yöntemi

Değer tiplerini [Object](../../object/)'e dönüştürmek için kutular. Enum tipleri için uygulama.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Enum](../../enum/) türü. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) değerini kutulamak için değer. |

### Dönüş Değeri

Kutu değerini tutan nesneye akıllı işaretçi.

## ObjectExt::Box(const T\&) yöntemi

Değer tiplerini [Object](../../object/)'e dönüştürmek için kutular. Enum olmayan tipler için uygulama.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | Kutulamak için değer. |

### Dönüş Değeri

Kutu değerini tutan nesneye akıllı işaretçi.

## ObjectExt::Box(const T\&) yöntemi

[Nullable](../../nullable/) tiplerini [Object](../../object/)'e dönüştürmek için kutular.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değer türü. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | Kutulamak için değer. |

### Dönüş Değeri

Kutu değerini tutan nesneye akıllı işaretçi.

## ObjectExt::Box(const String\&) yöntemi

Dize değerlerini kutular.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Kutulamak için değer. |

### Dönüş Değeri

Kutu değer veya null, kaynak dize null ise.

## Ayrıca Bakınız

* Sınıf [SmartPtr](../../smartptr/)
* Sınıf [Object](../../object/)
* Sınıf [ObjectExt](../)
* Sınıf [String](../../string/)
* Yapı [IsNullable](../../isnullable/)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)