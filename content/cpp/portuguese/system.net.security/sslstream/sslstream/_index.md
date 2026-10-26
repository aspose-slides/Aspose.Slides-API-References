---
title: SslStream()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 326
url: /pt/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) construtor

Constrói uma nova instância.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | O fluxo usado para enviar e receber dados. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) construtor

Constrói uma nova instância.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | O fluxo usado para enviar e receber dados. |
| leaveInnerStreamOpen | **bool** | Se verdadeiro, fechar a instância atual não afeta o 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) construtor

Constrói uma nova instância.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | O fluxo usado para enviar e receber dados. |
| leaveInnerStreamOpen | **bool** | Se verdadeiro, fechar a instância atual não afeta o 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | O delegado usado para validar o certificado fornecido pela parte remota. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) construtor

Constrói uma nova instância.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | O fluxo usado para enviar e receber dados. |
| leaveInnerStreamOpen | **bool** | Se verdadeiro, fechar a instância atual não afeta o 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | O delegado usado para validar o certificado fornecido pela parte remota. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | O delegado usado para selecionar o certificado usado para autenticação. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) construtor

Constrói uma nova instância.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | O fluxo usado para enviar e receber dados. |
| leaveInnerStreamOpen | **bool** | Se verdadeiro, fechar a instância atual não afeta o 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | O delegado usado para validar o certificado fornecido pela parte remota. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | O delegado usado para selecionar o certificado usado para autenticação. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | A política de criptografia. |

## Veja também

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Classe [Stream](../../../system.io/stream/)
* Classe [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)