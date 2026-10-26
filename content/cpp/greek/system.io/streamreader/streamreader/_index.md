---
title: StreamReader()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί ένα στιγμιότυπο του αντικειμένου StreamReader που διαβάζει χαρακτήρες από το καθορισμένο υποκείμενο ρεύμα χρησιμοποιώντας κωδικοποίηση UTF-8 και έναν buffer με προεπιλεγμένο μέγεθος 1024 bytes.
type: docs
weight: 1
url: /el/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο υποκείμενο ρεύμα χρησιμοποιώντας κωδικοποίηση UTF-8 και έναν buffer με προεπιλεγμένο μέγεθος 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Το υποκείμενο ρεύμα για ανάγνωση χαρακτήρων |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο υποκείμενο ρεύμα χρησιμοποιώντας κωδικοποίηση UTF-8 και έναν buffer με προεπιλεγμένο μέγεθος 1024 bytes. Μια παράμετρος καθορίζει εάν πρέπει να ενεργοποιηθεί η ανίχνευση σημείου σειράς byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Το υποκείμενο ρεύμα για ανάγνωση χαρακτήρων |
| detectEncodingFromByteOrderMarks | **bool** | True για ανίχνευση σημείων σειράς byte στην αρχή του ρεύματος, διαφορετικά false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο υποκείμενο ρεύμα χρησιμοποιώντας την καθορισμένη κωδικοποίηση και έναν buffer με προεπιλεγμένο μέγεθος 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Το υποκείμενο ρεύμα για ανάγνωση χαρακτήρων |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο υποκείμενο ρεύμα χρησιμοποιώντας την καθορισμένη κωδικοποίηση και έναν buffer με προεπιλεγμένο μέγεθος 1024 bytes. Μια παράμετρος καθορίζει εάν πρέπει να ενεργοποιηθεί η ανίχνευση σημείου σειράς byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Το υποκείμενο ρεύμα για ανάγνωση χαρακτήρων |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |
| detectEncodingFromByteOrderMarks | **bool** | True για ανίχνευση σημείων σειράς byte στην αρχή του ρεύματος, διαφορετικά false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο υποκείμενο ρεύμα χρησιμοποιώντας την καθορισμένη κωδικοποίηση και έναν buffer του καθορισμένου μεγέθους. Μια παράμετρος καθορίζει εάν πρέπει να ενεργοποιηθεί η ανίχνευση σημείου σειράς byte.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Το υποκείμενο ρεύμα για ανάγνωση χαρακτήρων |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |
| detectEncodingFromByteOrderMarks | **bool** | True για ανίχνευση σημείων σειράς byte στην αρχή του ρεύματος, διαφορετικά false |
| bufferSize | int | Το ελάχιστο μέγεθος του buffer σε bytes |

## StreamReader::StreamReader(const System::String\&) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο αρχείο χρησιμοποιώντας κωδικοποίηση UTF-8 και έναν buffer με προεπιλεγμένο μέγεθος 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Η διαδρομή του αρχείου για ανάγνωση χαρακτήρων |

## StreamReader::StreamReader(const System::String\&, bool) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο αρχείο χρησιμοποιώντας κωδικοποίηση UTF-8 και έναν buffer με προεπιλεγμένο μέγεθος 4096 bytes. Μια παράμετρος καθορίζει εάν πρέπει να ενεργοποιηθεί η ανίχνευση σημείου σειράς byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Η διαδρομή του αρχείου για ανάγνωση χαρακτήρων |
| detectEncodingFromByteOrderMarks | **bool** | True για ανίχνευση σημείων σειράς byte στην αρχή του αρχείου, διαφορετικά false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση και έναν buffer με προεπιλεγμένο μέγεθος 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Η διαδρομή του αρχείου για ανάγνωση χαρακτήρων |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο υποκείμενο ρεύμα χρησιμοποιώντας την καθορισμένη κωδικοποίηση και έναν buffer με προεπιλεγμένο μέγεθος 4096 bytes. Μια παράμετρος καθορίζει εάν πρέπει να ενεργοποιηθεί η ανίχνευση σημείου σειράς byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Η διαδρομή του αρχείου για ανάγνωση χαρακτήρων |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |
| detectEncodingFromByteOrderMarks | **bool** | True για ανίχνευση σημείων σειράς byte στην αρχή του αρχείου, διαφορετικά false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) κατασκευαστής

Δημιουργεί μια παρουσία του αντικειμένου [StreamReader](../) που διαβάζει χαρακτήρες από το συγκεκριμένο αρχείο χρησιμοποιώντας την καθορισμένη κωδικοποίηση και έναν buffer του καθορισμένου μεγέθους. Μια παράμετρος καθορίζει εάν πρέπει να ενεργοποιηθεί η ανίχνευση σημείου σειράς byte.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | Η διαδρομή του αρχείου για ανάγνωση χαρακτήρων |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Η κωδικοποίηση προς χρήση |
| detectEncodingFromByteOrderMarks | **bool** | True για ανίχνευση σημείων σειράς byte στην αρχή του αρχείου, διαφορετικά false |
| bufferSize | int | Το ελάχιστο μέγεθος του buffer σε bytes |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Stream](../../stream/)
* Class [StreamReader](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)