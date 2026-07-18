---
title: "System::Net::Security"
second_title: Aspose.Slides για Αναφορά API C++
description: 
type: docs
weight: 716
url: /el/system.net.security/
---
## Κλάσεις

| Class | Description |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Περιέχει τις μεθόδους για τη μεταφορά διαπιστευτηρίων μέσω μιας ροής. Τα αντικείμενα αυτής της κλάσης θα πρέπει να καταλαμβάνονται μόνο χρησιμοποιώντας τη συνάρτηση [System::MakeObject()](../system/makeobject/). Ποτέ μην δημιουργείτε στιγμιότυπο αυτού του τύπου στη στοίβα ή χρησιμοποιώντας τον τελεστή new, καθώς θα οδηγήσει σε σφάλματα χρόνου εκτέλεσης και/ή σφάλματα ελέγχου. Πάντα τυλίξτε αυτήν την κλάση σε δείκτη [System::SmartPtr](../system/smartptr/) και χρησιμοποιήστε αυτόν τον δείκτη για να τη μεταβιβάσετε σε συναρτήσεις ως όρισμα. |
| [SslStream](./sslstream/) | Μια ροή που χρησιμοποιεί το πρωτόκολλο SSL για την ταυτοποίηση του εξυπηρετητή και προαιρετικά του πελάτη. |
## Απαριθμήσεις

| Enum | Description |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Σημαίες αυθεντικοποίησης ειδικές για το WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | Απαριθμεί τα σφάλματα πολιτικής του SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Απαριθμεί τις πολιτικές κρυπτογράφησης. |
## Τύποι

| Typedef | Description |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Ένας αντιπρόσωπος χρήστη που χρησιμοποιείται για την επαλήθευση του απομακρυσμένου πιστοποιητικού SSL. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Ένας αντιπρόσωπος χρήστη που χρησιμοποιείται για την επιλογή τοπικού πιστοποιητικού SSL. |