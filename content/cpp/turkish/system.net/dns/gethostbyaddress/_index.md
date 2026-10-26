---
title: GetHostByAddress()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen IP adresinin dize temsili kullanılarak yeni bir IPHostEntry-class örneği oluşturur.
type: docs
weight: 14
url: /tr/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) metodu

IP adresinin dize temsili kullanılarak yeni bir IPHostEntry-class örneği oluşturur.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| address | [String](../../../system/string/) | IP adresinin dize temsili. |

### Dönüş Değeri

Yeni oluşturulmuş bir IPHostEntry-class örneği.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) metodu

Belirtilen IP adresi kullanılarak yeni bir IPHostEntry-class örneği oluşturur.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP adresi. |

### Dönüş Değeri

Yeni oluşturulmuş bir IPHostEntry-class örneği.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPHostEntry](../../iphostentry/)
* Sınıf [String](../../../system/string/)
* Sınıf [Dns](../)
* Sınıf [IPAddress](../../ipaddress/)
* Ad Alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)