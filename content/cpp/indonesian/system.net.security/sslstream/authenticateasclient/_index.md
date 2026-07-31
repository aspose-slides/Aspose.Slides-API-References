---
title: AuthenticateAsClient()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengautentikasi sisi klien dari koneksi.
type: docs
weight: 339
url: /id/system.net.security/sslstream/authenticateasclient/
---
## SslStream::AuthenticateAsClient(String) metode

Mengautentikasi sisi klien dari koneksi.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Nama server yang berbagi instance saat ini. |

## SslStream::AuthenticateAsClient(String, System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509CertificateCollection\>, System::Security::Authentication::SslProtocols, bool) metode

Mengautentikasi sisi klien dari koneksi.

```cpp
virtual void System::Net::Security::SslStream::AuthenticateAsClient(String targetHost, System::SharedPtr<System::Security::Cryptography::X509Certificates::X509CertificateCollection> clientCertificates, System::Security::Authentication::SslProtocols enabledSslProtocols, bool checkCertificateRevocation)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| targetHost | [String](../../../system/string/) | Nama server yang berbagi instance saat ini. |
| clientCertificates | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)\> | Sertifikat klien. |
| enabledSslProtocols | [System::Security::Authentication::SslProtocols](../../../system.security.authentication/sslprotocols/) | Protokol SSL yang digunakan untuk autentikasi. |
| checkCertificateRevocation | **bool** | Nilai yang menunjukkan apakah daftar pencabutan sertifikat harus diperiksa selama autentikasi. |

## Lihat Juga

* Enum [SslProtocols](../../../system.security.authentication/sslprotocols/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [SslStream](../)
* Class [X509CertificateCollection](../../../system.security.cryptography.x509certificates/x509certificatecollection/)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)