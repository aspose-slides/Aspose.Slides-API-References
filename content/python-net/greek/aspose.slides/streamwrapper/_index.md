---
title: StreamWrapper class
second_title: Aspose.Slides για Python μέσω .NET - Αναφορά API
description: 
type: docs
url: /el/aspose.slides/streamwrapper/
---
## StreamWrapper κλάση

Aspose.IO.Stream wrapper για τη διεπαφή COM.

Ο τύπος StreamWrapper εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`stream`](/slides/python-net/el/aspose.slides/streamwrapper/stream/) | Λαμβάνει μια ροή.<br/>            Μόνο-ανάγνωση **io.RawIOBase**. |
| [`can_read`](/slides/python-net/el/aspose.slides/streamwrapper/can_read/) | Λαμβάνει μια τιμή που υποδεικνύει αν η τρέχουσα ροή υποστηρίζει ανάγνωση.<br/>            Μόνο-ανάγνωση **bool**. |
| [`can_seek`](/slides/python-net/el/aspose.slides/streamwrapper/can_seek/) | Λαμβάνει μια τιμή που υποδεικνύει αν η τρέχουσα ροή υποστηρίζει αναζήτηση.<br/>            Μόνο-ανάγνωση **bool**. |
| [`can_write`](/slides/python-net/el/aspose.slides/streamwrapper/can_write/) | Λαμβάνει μια τιμή που υποδεικνύει αν η τρέχουσα ροή υποστηρίζει εγγραφή.<br/>            Μόνο-ανάγνωση **bool**. |
| [`length`](/slides/python-net/el/aspose.slides/streamwrapper/length/) | Λαμβάνει το μήκος σε byte της ροής.<br/>            Μόνο-ανάγνωση **int**. |
| [`position`](/slides/python-net/el/aspose.slides/streamwrapper/position/) | Λαμβάνει ή ορίζει τη θέση μέσα στην τρέχουσα ροή.<br/>            Μόνο-ανάγνωση **int**. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`close(self)`](/slides/python-net/el/aspose.slides/streamwrapper/close/#) | Κλείνει την τρέχουσα ροή και απελευθερώνει όλους τους πόρους. |
| [`flush(self)`](/slides/python-net/el/aspose.slides/streamwrapper/flush/#) | Καθαρίζει όλα τα buffers για αυτή τη ροή και προκαλεί την εγγραφή των αποθηκευμένων δεδομένων στη βασική συσκευή. |
| [`read(self, buffer, offset, count)`](/slides/python-net/el/aspose.slides/streamwrapper/read/#bytes-int-int) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προωθεί τη θέση μέσα στη ροή κατά τον αριθμό των byte που διαβάστηκαν. |
| [`read_byte(self)`](/slides/python-net/el/aspose.slides/streamwrapper/read_byte/#) | Διαβάζει ένα byte από τη ροή και προωθεί τη θέση μέσα στη ροή κατά ένα byte, ή επιστρέφει -1 εάν είναι στο τέλος της ροής. |
| [`seek(self, offset, origin)`](/slides/python-net/el/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Ορίζει τη θέση μέσα στην τρέχουσα ροή. |
| [`write(self, buffer, offset, count)`](/slides/python-net/el/aspose.slides/streamwrapper/write/#bytes-int-int) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προωθεί τη τρέχουσα θέση σε αυτή τη ροή κατά τον αριθμό των byte που γράφτηκαν. |
| [`write_byte(self, value)`](/slides/python-net/el/aspose.slides/streamwrapper/write_byte/#int) | Γράφει ένα byte στην τρέχουσα θέση στη ροή και προωθεί τη θέση μέσα στη ροή κατά ένα byte. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)