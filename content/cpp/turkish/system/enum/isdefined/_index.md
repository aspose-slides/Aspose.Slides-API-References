---
title: IsDefined()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değerin E enum tipinin bir üyesi olup olmadığını belirler.
type: docs
weight: 27
url: /tr/system/enum/isdefined/
---
## Enum::IsDefined(E) metod

Belirtilen değerin **E** enum tipinin bir üyesi olup olmadığını belirler.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | E | Kontrol edilecek değer |

### Dönüş Değeri

**value** bir **E** enum üyesiyse True, aksi takdirde false

## Enum::IsDefined(T) metod

Belirtilen değerin **T** enum tipinin bir üyesi olup olmadığını belirler.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T | Kontrol edilecek değer |

### Dönüş Değeri

**value** bir **T** enum üyesiyse True, aksi takdirde false

## Enum::IsDefined(const String\&) metod

Belirtilen isimle değerin **E** enum üyesi arasında olup olmadığını belirler.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../string/)\& | Kontrol edilecek isim |

### Dönüş Değeri

Belirtilen isimde bir **E** enum üyesi mevcutsa True, aksi takdirde false

## İlgili

* Typedef [UnderlyingType](../underlyingtype/)
* Sınıf [String](../../string/)
* Yapı [Enum](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)