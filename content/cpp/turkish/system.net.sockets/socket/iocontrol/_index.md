---
title: IOControl()
second_title: Aspose.Slides C++ için API Referansı
description: Soket için düşük seviyeli çalışma modlarını ayarlar.
type: docs
weight: 703
url: /tr/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod

Soket için düşük seviyeli çalışma modlarını ayarlar.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ioControlCode | **int32_t** | Gerçekleştirilecek işlemin kontrol kodu. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Giriş verilerini içeren bayt dizisi. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Çıkış verilerini içeren bayt dizisi. |

### Dönüş Değeri

**optionOutValue** parametresindeki bayt sayısı.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metod

Soket için düşük seviyeli çalışma modlarını ayarlar.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | Gerçekleştirilecek işlemin kontrol kodu. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Giriş verilerini içeren bayt dizisi. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Çıkış verilerini içeren bayt dizisi. |

### Dönüş Değeri

**optionOutValue** parametresindeki bayt sayısı.

## Ayrıca Bakınız

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Socket](../)
* İsim Alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)