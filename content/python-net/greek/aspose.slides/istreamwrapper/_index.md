---
title: IStreamWrapper class
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/istreamwrapper/
---
## IStreamWrapper κλάση

Aspose.IO.Stream wrapper for COM interface.

The IStreamWrapper type exposes the following members:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`stream`](/slides/python-net/el/aspose.slides/istreamwrapper/stream/) | Λαμβάνει μια ροή.<br/>            Μόνο-ανάγνωση **io.RawIOBase**. |
| [`can_read`](/slides/python-net/el/aspose.slides/istreamwrapper/can_read/) | Λαμβάνει τιμή που υποδεικνύει εάν η τρέχουσα ροή υποστηρίζει ανάγνωση.<br/>            Μόνο-ανάγνωση **bool**. |
| [`can_seek`](/slides/python-net/el/aspose.slides/istreamwrapper/can_seek/) | Λαμβάνει τιμή που υποδεικνύει εάν η τρέχουσα ροή υποστηρίζει αναζήτηση.<br/>            Μόνο-ανάγνωση **bool**. |
| [`can_write`](/slides/python-net/el/aspose.slides/istreamwrapper/can_write/) | Λαμβάνει τιμή που υποδεικνύει εάν η τρέχουσα ροή υποστηρίζει εγγραφή.<br/>            Μόνο-ανάγνωση **bool**. |
| [`length`](/slides/python-net/el/aspose.slides/istreamwrapper/length/) | Λαμβάνει το μήκος σε bytes της ροής.<br/>            Μόνο-ανάγνωση **int**. |
| [`position`](/slides/python-net/el/aspose.slides/istreamwrapper/position/) | Λαμβάνει τη θέση μέσα στην τρέχουσα ροή.<br/>            Μόνο-ανάγνωση **int**. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`close(self)`](/slides/python-net/el/aspose.slides/istreamwrapper/close/#) | Κλείνει την τρέχουσα ροή και απελευθερώνει τυχόν πόρους. |
| [`flush(self)`](/slides/python-net/el/aspose.slides/istreamwrapper/flush/#) | Καθαρίζει όλες τις προσωρινές μνήμες για αυτή τη ροή και προκαλεί την εγγραφή των προσωρινών δεδομένων στη βασική συσκευή. |
| [`read(self, buffer, offset, count)`](/slides/python-net/el/aspose.slides/istreamwrapper/read/#bytes-int-int) | Διαβάζει μια ακολουθία byte από την τρέχουσα ροή και προχωρά τη θέση στη ροή κατά τον αριθμό των byte που διαβάστηκαν. |
| [`read_byte(self)`](/slides/python-net/el/aspose.slides/istreamwrapper/read_byte/#) | Διαβάζει ένα byte από τη ροή και προχωρά τη θέση στη ροή κατά ένα byte, ή επιστρέφει -1 εάν είναι στο τέλος της ροής. |
| [`seek(self, offset, origin)`](/slides/python-net/el/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Ορίζει τη θέση στη τρέχουσα ροή |
| [`write(self, buffer, offset, count)`](/slides/python-net/el/aspose.slides/istreamwrapper/write/#bytes-int-int) | Γράφει μια ακολουθία byte στην τρέχουσα ροή και προχωρά τη θέση στη ροή κατά τον αριθμό των byte που γράφτηκαν. |
| [`write_byte(self, value)`](/slides/python-net/el/aspose.slides/istreamwrapper/write_byte/#int) | Γράφει ένα byte στην τρέχουσα θέση στη ροή και προχωρά τη θέση στη ροή κατά ένα byte. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)