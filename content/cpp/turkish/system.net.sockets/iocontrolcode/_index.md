---
title: IOControlCode
second_title: Aspose.Slides for C++ API Referansı
description: IO kontrol kodlarını listeler.
type: docs
weight: 157
url: /tr/system.net.sockets/iocontrolcode/
---
## IOControlCode enum

[IO](../../system.io/) kontrol kodlarını listeler.

```cpp
enum class IOControlCode : int64_t
```

### Değerler

| Name | Value | Description |
| --- | --- | --- |
| AsyncIO | -2147195267 | Soketin asenkron I/O modunu etkinleştirir veya devre dışı bırakır. |
| NonBlockingIO | -2147195266 | Soketi bloklamayan olarak işaretler. |
| DataToRead | 1074030207 | Okunabilecek bayt sayısını döndürür. |
| OobDataRead | 1074033415 | Alınmayı bekleyen out-of-band (bant dışı) veri hakkında bilgi döndürür. |
| AssociateHandle | -2013265919 | Bu soketi bir yardımcı arayüzün belirtilen tutamağıyla ilişkilendirir. |
| EnableCircularQueuing | 671088642 | Gelen mesaj kuyrukları dolduğunda en eski kuyruğa alınan datagramı gelenle değiştirir. |
| Flush | 671088644 | Bu sokete ilişkin gönderme kuyruğunun mevcut içeriğini siler. |
| GetBroadcastAddress | 1207959557 | Mevcut soketin adres ailesi için yayın adresini içeren bir SOCKADDR yapısını döndürür. |
| GetExtensionFunctionPointer | -939524090 | İlgili hizmet sağlayıcı tarafından desteklenen belirtilen uzantı işlevine bir pointer alır. |
| GetQos | -939524089 | Soket ile ilişkili QOS yapısını alır. |
| GetGroupQos | -939524088 | Soket grubu için QOS özelliklerini döndürür. |
| MultipointLoopback | -2013265911 | Bir uygulamanın yerel bilgisayarda bir multicast oturumunda gönderdiği verilerin (aynı soket olmayabilir) döngü geri dönüş arayüzündeki multicast hedef grubuna katılmış bir soket tarafından alınıp alınmayacağını kontrol eder. |
| MulticastScope | -2013265910 | Bir yönlendiricinin bir multicast paketini kaç kez iletebileceğini (TTL veya hop sayısı olarak da bilinir) kontrol eder. |
| SetQos | -2013265909 | Soket için QOS özelliklerini ayarlar. |
| SetGroupQos | -2013265908 | Soket grubu için QOS özelliklerini ayarlar. |
| TranslateHandle | -939524083 | Bir yardımcı arayüz bağlamında geçerli olan soket için bir tutamak döndürür. |
| RoutingInterfaceQuery | -939524076 | Belirtilen uzak adrese bağlanmak için kullanılabilecek arayüz adreslerini döndürür. |
| RoutingInterfaceChange | -2013265899 | Uzak uç noktaya erişmek için kullanılan yerel arayüz değiştiğinde bir bildirim almayı etkinleştirir. |
| AddressListQuery | 1207959574 | Soketin bağlanabileceği yerel arayüzlerin listesini döndürür. |
| AddressListChange | 671088663 | Soketin protokol ailesine ait yerel arayüz listesi değiştiğinde bir bildirim almayı etkinleştirir. |
| QueryTargetPnpHandle | 1207959576 | Temel sağlayıcının SOCKET tutamacını alır. |
| NamespaceChange | -2013265895 | Bir ad alanı sorgusu geçersiz olduğunda soketin bildirim alıp almayacağını kontrol eder. |
| AddressListSort | -939524071 | Bağlantı kurmak için en uygun adresi belirlemek amacıyla IPv6 ve IPv4 hedef adres listesini sıralar. |
| ReceiveAll | -1744830463 | Ağda tüm IPv4 paketlerini almayı etkinleştirir. |
| ReceiveAllMulticast | -1744830462 | Ağda tüm multicast IPv4 paketlerini almayı etkinleştirir. |
| ReceiveAllIgmpMulticast | -1744830461 | Ağda tüm IGMP paketlerini almayı etkinleştirir. |
| KeepAliveValues | -1744830460 | TCP keep-alive paketlerinin gönderilmesini ve gönderim aralığını kontrol eder. |
| AbsorbRouterAlert | -1744830459 | Bu değer Winsock 2 'SIO_ABSORB_RTRALERT' sabitine eşittir. |
| UnicastInterface | -1744830458 | Giden tekil (unicast) paketler için kullanılan arayüzü ayarlar. |
| LimitBroadcasts | -1744830457 | Bu değer Winsock 2 'SIO_LIMIT_BROADCASTS' sabitine eşittir. |
| BindToInterface | -1744830456 | Soketi belirtilen bir arayüz indeksine bağlar. |
| MulticastInterface | -1744830455 | Giden multicast paketleri için kullanılan arayüzü ayarlar. |
| AddMulticastGroupOnInterface | -1744830454 | Bir arayüzün indeksine göre tanımlanan bir multicast grubuna katılır. |
| DeleteMulticastGroupFromInterface | -1744830453 | Soketi bir multicast grubundan çıkarır. |

## Ayrıca Bakınız

* Ad Alanı [System::Net::Sockets](../)
* Kütüphane [Aspose.Slides](../../)