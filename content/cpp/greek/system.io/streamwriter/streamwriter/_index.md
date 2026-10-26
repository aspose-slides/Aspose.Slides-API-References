---
title: StreamWriter()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί μια παρουσία του αντικειμένου StreamWriter που γράφει χαρακτήρες στην καθορισμένη υποκείμενη ροή χρησιμοποιώντας κωδικοποίηση UTF-8 και έναν buffer με προεπιλεγμένο μέγεθος 1024 byte.
type: docs
weight: 1
url: /el/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](../) που γράφει χαρακτήρες στην καθορισμένη υποκείμενη ροή χρησιμοποιώντας κωδικοποίηση UTF-8 και έναν buffer με προεπιλεγμένο μέγεθος 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Η υποκείμενη ροή για την εγγραφή χαρακτήρων |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](../) που γράφει χαρακτήρες στην καθορισμένη υποκείμενη ροή χρησιμοποιώντας την καθορισμένη κωδικοποίηση και έναν buffer με προεπιλεγμένο μέγεθος 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Η υποκείμενη ροή για την εγγραφή χαρακτήρων |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](../) που γράφει χαρακτήρες στην καθορισμένη υποκείμενη ροή χρησιμοποιώντας την καθορισμένη κωδικοποίηση και έναν buffer του καθορισμένου μεγέθους. Μία παράμετρος καθορίζει αν η υποκείμενη ροή πρέπει να κλείσει όταν το αντικείμενο [StreamWriter](../) αποδεσμευτεί.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Η υποκείμενη ροή για την εγγραφή χαρακτήρων |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |
| buffer_size | int | Το ελάχιστο μέγεθος του buffer σε byte |
| leave_open | **bool** | Καθορίζει αν η υποκείμενη ροή πρέπει να παραμείνει ανοιχτή μετά το κλείσιμο του τρέχοντος αντικειμένου [StreamWriter](../) |

## StreamWriter::StreamWriter(const String\&) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](../) που γράφει χαρακτήρες στο καθορισμένο αρχείο χρησιμοποιώντας κωδικοποίηση UTF-8 και έναν buffer με προεπιλεγμένο μέγεθος 1024 byte.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου για την εγγραφή χαρακτήρων |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](../) που γράφει χαρακτήρες στο καθορισμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση και έναν buffer με προεπιλεγμένο μέγεθος 1024 byte. Μία παράμετρος καθορίζει αν τα δεδομένα πρέπει να προσαρτηθούν στο αρχείο ή αν το αρχείο πρέπει να αντικατασταθεί.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου για την εγγραφή χαρακτήρων |
| append | **bool** | Καθορίζει αν τα δεδομένα πρέπει να προσαρτηθούν στο καθορισμένο αρχείο (true) ή αν το αρχείο πρέπει να αντικατασταθεί (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamWriter](../) που γράφει χαρακτήρες στο καθορισμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση και το μέγεθος του buffer. Μία παράμετρος καθορίζει αν τα δεδομένα πρέπει να προσαρτηθούν στο αρχείο ή αν το αρχείο πρέπει να αντικατασταθεί.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Η διαδρομή του αρχείου για την εγγραφή χαρακτήρων |
| append | **bool** | Καθορίζει αν τα δεδομένα πρέπει να προσαρτηθούν στο καθορισμένο αρχείο (true) ή αν το αρχείο πρέπει να αντικατασταθεί (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |
| buffer_size | int | Το μέγεθος του buffer προς χρήση |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)