---
title: "System::Net::Sockets"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 729
url: /id/system.net.sockets/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Details_SocketException](./details_socketexception/) | Mewakili pengecualian yang dilempar ketika terjadi kesalahan socket. Jangan pernah membuat instance kelas ini secara manual. Gunakan kelas SocketException sebagai gantinya. Jangan pernah membungkus instance kelas SocketException ke dalam [System::SmartPtr](../system/smartptr/). |
| [IPPacketInformation](./ippacketinformation/) | Mewakili informasi tentang paket. Objek dari kelas ini hanya boleh dialokasikan dengan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau dengan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk meneruskan ke fungsi sebagai argumen. |
| [LingerOption](./lingeroption/) | Menentukan apakah socket akan tetap terhubung setelah pemanggilan metode Close() atau Close(). Ini juga menentukan periode socket tetap terhubung jika pengiriman data berlanjut. Objek dari kelas ini hanya boleh dialokasikan dengan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau dengan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk meneruskan ke fungsi sebagai argumen. |
| [NetworkStream](./networkstream/) | Menyediakan aliran dasar data untuk akses jaringan. Objek dari kelas ini hanya boleh dialokasikan dengan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau dengan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk meneruskan ke fungsi sebagai argumen. |
| [Socket](./socket/) | Kelas [Socket](./socket/) mengimplementasikan antarmuka Berkeley sockets. |
| [TcpClient](./tcpclient/) | Mewakili klien untuk layanan jaringan TCP. Objek dari kelas ini hanya boleh dialokasikan dengan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau dengan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk meneruskan ke fungsi sebagai argumen. |
| [TcpListener](./tcplistener/) | Mewakili pendengar untuk layanan jaringan TCP. Objek dari kelas ini hanya boleh dialokasikan dengan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau dengan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk meneruskan ke fungsi sebagai argumen. |
| [UdpClient](./udpclient/) | Menyediakan layanan jaringan User Datagram Protocol (UDP). Objek dari kelas ini hanya boleh dialokasikan dengan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau dengan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk meneruskan ke fungsi sebagai argumen. |
## Fungsi

| Fungsi | Deskripsi |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
| **bool** [operator!=](./operator_not_equal/)([IPPacketInformation](./ippacketinformation/), [IPPacketInformation](./ippacketinformation/)) |  |
## Enum

| Enum | Deskripsi |
| --- | --- |
| [SocketType](./sockettype/) | Menumerasikan tipe socket. |
| [AddressFamily](./addressfamily/) | Menumerasikan keluarga alamat. |
| [IOControlCode](./iocontrolcode/) | Menumerasikan kode kontrol [IO](../system.io/). |
| [ProtocolFamily](./protocolfamily/) | Menumerasikan keluarga protokol. |
| [ProtocolType](./protocoltype/) | Menumerasikan tipe protokol. |
| [SelectMode](./selectmode/) | Menentukan mode untuk polling status socket. |
| [SocketError](./socketerror/) | Menumerasikan tipe error socket. |
| [SocketFlags](./socketflags/) | Menyediakan nilai konstan untuk pesan socket. |
| [SocketOptionLevel](./socketoptionlevel/) | Mendefinisikan level opsi socket untuk kelas '[Socket](./socket/)'. |
| [SocketOptionName](./socketoptionname/) | Mendefinisikan nama opsi socket untuk kelas [Socket](./socket/). |
| [SocketShutdown](./socketshutdown/) | Mendefinisikan konstanta yang digunakan oleh metode [Socket.Shutdown](./socket/shutdown/). |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [SocketException](./socketexception/) |  |