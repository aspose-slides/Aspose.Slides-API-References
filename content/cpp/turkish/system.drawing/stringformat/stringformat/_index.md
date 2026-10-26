---
title: StringFormat()
second_title: Aspose.Slides for C++ API Referansı
description: StringFormat sınıfının yeni bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() yapıcı


[StringFormat](../) sınıfının yeni bir örneğini oluşturur.

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) yapıcı


[StringFormat](../) sınıfının belirtilen format bayrakları ve dil ile yeni bir örneğini oluşturur.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Nesnenin temsil edeceği dize biçimini belirten StringFormatFlags enum değerinin bit düzeyinde bir kombinasyonu |
| language | **int32_t** | Metnin dili |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) yapıcı


Kopya yapıcı.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Kopyalanacak [StringFormat](../) nesnesi |

## Ayrıca Bakınız

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [StringFormat](../)
* Ad alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)