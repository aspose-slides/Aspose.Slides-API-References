---
title: AppendFormat()
second_title: Aspose.Slides için C++ API Referansı
description: Biçimlendirilmiş dizeyi builder'a ekler.
type: docs
weight: 131
url: /tr/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) metot


Biçimlendirilmiş dizeyi builder'a ekler.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TArgs | Argüman tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Biçim dizesi. |
| args | const TArgs\&... | Biçim dizesi konumlarına eklemek için argümanlar. |

### Dönüş Değeri

Bu işaretçi.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) metot


Biçimlendirilmiş dizeyi builder'a ekler.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TArgs | Argüman tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Biçim sağlayıcı; yok sayıldı. |
| format | const [String](../../../system/string/)\& | Biçim dizesi. |
| args | const TArgs\&... | Biçim dizesi konumlarına eklemek için argümanlar. |

### Dönüş Değeri

Bu işaretçi.

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [StringBuilder](../)
* Sınıf [String](../../../system/string/)
* Sınıf [IFormatProvider](../../../system/iformatprovider/)
* Ad Alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)