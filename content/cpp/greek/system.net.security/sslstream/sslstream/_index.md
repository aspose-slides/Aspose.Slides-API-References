---
title: SslStream()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο αντικείμενο.
type: docs
weight: 326
url: /el/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Η ροή που χρησιμοποιείται για αποστολή και λήψη δεδομένων. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Η ροή που χρησιμοποιείται για αποστολή και λήψη δεδομένων. |
| leaveInnerStreamOpen | **bool** | Αν είναι true, το κλείσιμο της τρέχουσας παρουσίας δεν επηρεάζει το 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Η ροή που χρησιμοποιείται για αποστολή και λήψη δεδομένων. |
| leaveInnerStreamOpen | **bool** | Αν είναι true, το κλείσιμο της τρέχουσας παρουσίας δεν επηρεάζει το 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Το delegate που χρησιμοποιείται για την επικύρωση του πιστοποιητικού που παρέχεται από το απομακρυσμένο μέρος. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Η ροή που χρησιμοποιείται για αποστολή και λήψη δεδομένων. |
| leaveInnerStreamOpen | **bool** | Αν είναι true, το κλείσιμο της τρέχουσας παρουσίας δεν επηρεάζει το 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Το delegate που χρησιμοποιείται για την επικύρωση του πιστοποιητικού που παρέχεται από το απομακρυσμένο μέρος. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Το delegate που χρησιμοποιείται για την επιλογή του πιστοποιητικού που χρησιμοποιείται για την αυθεντικοποίηση. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Η ροή που χρησιμοποιείται για αποστολή και λήψη δεδομένων. |
| leaveInnerStreamOpen | **bool** | Αν είναι true, το κλείσιμο της τρέχουσας παρουσίας δεν επηρεάζει το 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Το delegate που χρησιμοποιείται για την επικύρωση του πιστοποιητικού που παρέχεται από το απομακρυσμένο μέρος. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Το delegate που χρησιμοποιείται για την επιλογή του πιστοποιητικού που χρησιμοποιείται για την αυθεντικοποίηση. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | Η πολιτική κρυπτογράφησης. |

## Δείτε επίσης

* Απαριθμητικό [EncryptionPolicy](../../encryptionpolicy/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Ορισμός τύπου [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Ορισμός τύπου [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [SslStream](../)
* Χώρος ονομάτων [System::Net::Security](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)