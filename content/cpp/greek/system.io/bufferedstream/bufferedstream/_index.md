---
title: BufferedStream()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα αντικείμενο BufferedStream που περιβάλλει την καθορισμένη ροή και χρησιμοποιεί έναν buffer μήκους 4096 bytes.
type: docs
weight: 1
url: /el/system.io/bufferedstream/bufferedstream/
---
## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&) constructor

Δημιουργεί ένα αντικείμενο [BufferedStream](../) που περιβάλλει τη συγκεκριμένη ροή και χρησιμοποιεί έναν buffer μεγέθους 4096 byte.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Το υποκείμενο αντικείμενο [Stream](../../stream/) |

## BufferedStream::BufferedStream(const SharedPtr\<Stream\>\&, int) constructor

Δημιουργεί ένα αντικείμενο [BufferedStream](../) που περιβάλλει τη συγκεκριμένη ροή και χρησιμοποιεί έναν buffer του καθορισμένου μεγέθους.

```cpp
System::IO::BufferedStream::BufferedStream(const SharedPtr<Stream> &stream, int bufferSize)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Το υποκείμενο αντικείμενο [Stream](../../stream/) |
| bufferSize | int | Το μέγεθος του buffer σε bytes |

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [Stream](../../stream/)
* Κλάση [BufferedStream](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)