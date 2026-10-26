---
title: GetHostEntry()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen ana bilgisayar adı veya IP adresi içeren dizeyi kullanarak yeni bir IPHostEntry-sınıfı örneği oluşturur.
type: docs
weight: 79
url: /tr/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) yöntemi

Belirtilen ana bilgisayar adı veya IP adresi içeren dizeyi kullanarak yeni bir IPHostEntry-sınıfı örneği oluşturur.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Ana bilgisayar adı veya IP adresi içeren bir dize. |

### Dönüş Değeri

Yeni oluşturulmuş bir IPHostEntry-sınıfı örneği.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) yöntemi

Belirtilen IP adresini kullanarak yeni bir IPHostEntry-sınıfı örneği oluşturur.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP adresi. |

### Dönüş Değeri

Yeni oluşturulmuş bir IPHostEntry-sınıfı örneği.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IPHostEntry](../../iphostentry/)
* Sınıf [String](../../../system/string/)
* Sınıf [Dns](../)
* Sınıf [IPAddress](../../ipaddress/)
* Ad Alanı [System::Net](../../)
* Library [Aspose.Slides](../../../)