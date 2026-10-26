---
title: Write()
second_title: Aspose.Slides για C++ Αναφορά API
description: Γράφει το καθορισμένο υποσύνολο byte από τον καθορισμένο πίνακα byte στη βασική ροή.
type: docs
weight: 66
url: /el/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο byte από τον καθορισμένο πίνακα byte στη βασική ροή.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Δείκτης βάσης 0 του στοιχείου στο **buffer** από όπου αρχίζει το υποσύνολο για εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων του υποσυνόλου προς εγγραφή |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο byte από τον καθορισμένο πίνακα byte στη βασική ροή.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Δείκτης βάσης 0 του στοιχείου στο **buffer** από όπου αρχίζει το υποσύνολο για εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων του υποσυνόλου προς εγγραφή |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)