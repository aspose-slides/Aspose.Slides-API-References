---
title: SocketOptionName
second_title: Aspose.Slides C++ API Referansı
description: Socket sınıfı için soket seçenek adlarını tanımlar.
type: docs
weight: 248
url: /tr/system.net.sockets/socketoptionname/
---
## SocketOptionName enum

Socket seçeneği adlarını [Socket](../socket/) sınıfı için tanımlar.

```cpp
enum class SocketOptionName
```

### Değerler

| İsim | Değer | Açıklama |
| --- | --- | --- |
| Debug | 1 | Hata ayıklama bilgilerini kaydeder. |
| AcceptConnection | 2 | Bir soketin gelen bir bağlantıyı dinleyip dinlemediğini gösterir. |
| ReuseAddress | 4 | Bir soketin zaten kullanımda olan bir adrese bağlanıp bağlanamayacağını gösterir. |
| KeepAlive | 8 | 'Keep-Alive' paketlerini bir soket bağlantısı için etkinleştirir. |
| DontRoute | 16 | Bir paketin doğrudan ara yüz adreslerine gönderilip gönderilmediğini gösterir. |
| Broadcast | 32 | Bir soketin yayın mesajlarını gönderip gönderemeyeceğini gösterir. |
| UseLoopback | 64 | Mümkün olduğunda donanımı atlar. |
| Linger | 128 | Sistem, veriyi iletileene kadar kapatma girişiminde süreci engelleyecektir. |
| OutOfBandInline | 256 | Normal veri akışında out-of-band verisini alır. |
| DontLinger | n/a | Bir soketin linger olmadan kapatılıp kapatılmayacağını gösterir. |
| ExclusiveAddressUse | n/a | Bir soket, bağlanan adresi yalnızca kendisi kullanacaktır. |
| SendBuffer | 4097 | Gönderme tamponunun boyutunu belirtir. |
| ReceiveBuffer | 4098 | Alma tamponunun boyutunu belirtir. |
| SendLowWater | 4099 | Gönderme işlemleri için minimum veri miktarını belirtir. |
| ReceiveLowWater | 4100 | Alma işlemleri için minimum veri miktarını belirtir. |
| SendTimeout | 4101 | Eşzamanlı gönderme işlemleri için zaman aşımını belirtir. |
| ReceiveTimeout | 4102 | Eşzamanlı alma işlemleri için zaman aşımını belirtir. |
| Error | 4103 | Hata durumunu döndürür ve temizler. |
| Type | 4104 | Bir soket türünü döndürür. |
| ReuseUnicastPort | 12295 | Sistem, çıkış bağlantıları için geçici port tahsisinde gecikme yapıp yapmayacağını gösterir. |
| MaxConnections | 2147483647 | Bu seçenek desteklenmez. Dinleme için maksimum kuyruk uzunluğunu belirtmekte kullanılmıştır. |
| IPOptions | 1 | Giden veri paketlerine eklenmesi gereken IP seçeneğini belirtir. |
| HeaderIncluded | 2 | Başlık, giden veri paketlerine eklenir. |
| TypeOfService | 3 | IP başlığının hizmet alanı tipini değiştirir. |
| IpTimeToLive | 4 | IP zaman aşımı süresi. |
| MulticastInterface | 9 | Giden çoklu yayın paketleri için ara yüzü ayarlar. |
| MulticastTimeToLive | 10 | IP çoklu yayın zaman aşımı süresi. |
| MulticastLoopback | 11 | IP çoklu yayın döngüsü. |
| AddMembership | 12 | Bir IP grup üyeliği ekler. |
| DropMembership | 13 | Bir IP grup üyeliğini bırakır. |
| DontFragment | 14 | IP veri paketlerini bölmez. |
| AddSourceMembership | 15 | IP grup/kaynağa katılır. |
| DropSourceMembership | 16 | IP grup/kaynağı bırakır. |
| BlockSource | 17 | IP grup/kaynağı engeller. |
| UnblockSource | 18 | IP grup/kaynağının engelini kaldırır. |
| PacketInformation | 19 | IPv4 için paket bilgilerini alır. |
| HopLimit | 21 | Paketin HOP sayısını içeren bir tamsayı verir. |
| IPProtectionLevel | 23 | IPv6 soketinin belirtilen kapsamla sınırlanmasını etkinleştirir. |
| IPv6Only | 27 | Soket yalnızca IPv6 paketleri göndermek ve almakla sınırlıdır. |
| NoDelay | 1 | Gönderme paketlerini birleştirmek için Nagle algoritmasını devre dışı bırakır. |
| BsdUrgent | 2 | RFC-1222'de tanımlandığı gibi acil veriyi kullanır. |
| Expedited | 2 | RFC-1222'de tanımlandığı gibi hızlı veriyi kullanır. |
| NoChecksum | 1 | UDP veri paketlerini kontrol toplamı sıfır olarak gönderir. |
| ChecksumCoverage | 20 | UDP kontrol toplamı kapsamasını ayarlar veya alır. |
| UpdateAcceptContext | 28683 | Bir istemci soketini dinleme soketinin aynı özellikleriyle günceller. |
| UpdateConnectContext | 28688 | Bir istemci soketini dinleme soketinin aynı özellikleriyle günceller. |

## See Also

* Namespace [System::Net::Sockets](../)
* Library [Aspose.Slides](../../)