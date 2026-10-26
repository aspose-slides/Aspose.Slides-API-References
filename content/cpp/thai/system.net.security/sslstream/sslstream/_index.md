---
title: SslStream()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอินสแตนซ์ใหม่.
type: docs
weight: 326
url: /th/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้สำหรับการส่งและรับข้อมูล. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้สำหรับการส่งและรับข้อมูล. |
| leaveInnerStreamOpen | **bool** | หากเป็น true, การปิดอินสแตนซ์ปัจจุบันจะไม่มีผลต่อ 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้สำหรับการส่งและรับข้อมูล. |
| leaveInnerStreamOpen | **bool** | หากเป็น true, การปิดอินสแตนซ์ปัจจุบันจะไม่มีผลต่อ 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | ตัวแทนที่ใช้ในการตรวจสอบใบรับรองที่จัดหามาจากฝ่ายระยะไกล. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้สำหรับการส่งและรับข้อมูล. |
| leaveInnerStreamOpen | **bool** | หากเป็น true, การปิดอินสแตนซ์ปัจจุบันจะไม่มีผลต่อ 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | ตัวแทนที่ใช้ในการตรวจสอบใบรับรองที่จัดหามาจากฝ่ายระยะไกล. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | ตัวแทนที่ใช้ในการเลือกใบรับรองที่ใช้สำหรับการตรวจสอบความถูกต้อง. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) คอนสตรัคเตอร์

สร้างอินสแตนซ์ใหม่.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | สตรีมที่ใช้สำหรับการส่งและรับข้อมูล. |
| leaveInnerStreamOpen | **bool** | หากเป็น true, การปิดอินสแตนซ์ปัจจุบันจะไม่มีผลต่อ 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | ตัวแทนที่ใช้ในการตรวจสอบใบรับรองที่จัดหามาจากฝ่ายระยะไกล. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | ตัวแทนที่ใช้ในการเลือกใบรับรองที่ใช้สำหรับการตรวจสอบความถูกต้อง. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | นโยบายการเข้ารหัส. |

## ดูเพิ่มเติม

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* คลาส [Stream](../../../system.io/stream/)
* คลาส [SslStream](../)
* เนมสเปซ [System::Net::Security](../../)
* ไลบรารี [Aspose.Slides](../../../)