---
title: "System::Net::Sockets"
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 729
url: /tr/system.net.sockets/
---
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Bir soket hatası oluştuğunda fırlatılan istisnayı temsil eder. Bu sınıfın örneklerini manuel olarak oluşturmayın. Bunun yerine SocketException sınıfını kullanın. SocketException sınıfı örneklerini [System::SmartPtr](../system/smartptr/) içine asla sarmalayın. |
| [IPPacketInformation](./ippacketinformation/) | Paketin bilgi içeriğini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına (stack) veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [LingerOption](./lingeroption/) | Bir soketin Close() veya Close() yöntemlerine çağrı yapıldıktan sonra bağlanmış kalıp kalmayacağını belirtir. Ayrıca, veri gönderimi devam ederse soketin bağlı kalacağı süreyi belirtir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [NetworkStream](./networkstream/) | Ağ erişimi için verinin temel akışını sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [Socket](./socket/) | [Socket](./socket/) sınıfı Berkeley soket arayüzünü uygular. |
| [TcpClient](./tcpclient/) | TCP ağ hizmetleri için bir istemciyi temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [TcpListener](./tcplistener/) | TCP ağ hizmetleri için bir dinleyiciyi temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [UdpClient](./udpclient/) | Kullanıcı Datagram Protokolü (UDP) ağ hizmetlerini sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
## Fonksiyonlar

| Fonksiyon | Açıklama |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
## Enum'lar

| Enum | Açıklama |
| --- | --- |
| [SocketType](./sockettype/) | Soket tiplerini listeler. |
| [AddressFamily](./addressfamily/) | Adres ailelerini listeler. |
| [IOControlCode](./iocontrolcode/) | [IO](../system.io/) kontrol kodlarını listeler. |
| [ProtocolFamily](./protocolfamily/) | Protokol ailelerini listeler. |
| [ProtocolType](./protocoltype/) | Protokol tiplerini listeler. |
| [SelectMode](./selectmode/) | Soket durumunu sorgulama modunu belirtir. |
| [SocketError](./socketerror/) | Soket hata tiplerini listeler. |
| [SocketFlags](./socketflags/) | Soket mesajları için sabit değerler sağlar. |
| [SocketOptionLevel](./socketoptionlevel/) | '[Socket](./socket/)' sınıfı için soket seçenek seviyelerini tanımlar. |
| [SocketOptionName](./socketoptionname/) | [Socket](./socket/) sınıfı için soket seçenek adlarını tanımlar. |
| [SocketShutdown](./socketshutdown/) | [Socket.Shutdown](./socket/shutdown/) yöntemi tarafından kullanılan sabitleri tanımlar. |
## Typedef'lar

| Typedef | Açıklama |
| --- | --- |
| [SocketException](./socketexception/) |  |