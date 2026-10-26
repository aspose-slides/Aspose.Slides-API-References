---
title: Marshal
second_title: Αναφορά API Aspose.Slides για C++
description: Παρέχει υλοποίηση marshaling. Μόνο για συμβατότητα με μεταφρασμένο κώδικα, καθώς δεν υποστηρίζεται κώδικας διαχείρισης στην πλευρά C++. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιοτύπων. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με οποιονδήποτε τρόπο.
type: docs
weight: 14
url: /el/system.runtime.interopservices/marshal/
---
## Marshal κλάση

Παρέχει υλοποίηση marshaling. Μόνο για συμβατότητα με μεταφρασμένο κώδικα, καθώς δεν υποστηρίζεται κώδικας διαχείρισης στην πλευρά C++. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες στιγμιοτύπων. Δεν πρέπει ποτέ να δημιουργείτε στιγμιότυπα του με οποιονδήποτε τρόπο.

```cpp
class Marshal
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static IntPtr [AllocHGlobal](./allochglobal/)(**int32_t**) | Κατανέμει μη διαχειριζόμενη μνήμη. |
| static IntPtr [AllocHGlobal](./allochglobal/)(IntPtr) | Κατανέμει μη διαχειριζόμενη μνήμη. |
| static void [Copy](./copy/)(const IntPtr, container\&&, int, int) | Εφαρμόζει τη σημασιολογία public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const void *, container\&&, int, int) | Εφαρμόζει τη σημασιολογία public static void Copy(IntPtr source, byte[] destination, int startIndex, int length). |
| static void [Copy](./copy/)(const container\&, int, void *, int) | Εφαρμόζει τη σημασιολογία public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [Copy](./copy/)(const container\&, int, IntPtr, int) | Εφαρμόζει τη σημασιολογία public static void Copy(char[] source, int startIndex, IntPtr destination, int length). |
| static void [FreeHGlobal](./freehglobal/)(IntPtr) | Ελευθερώνει μη διαχειριζόμενη μνήμη. |
| static TDelegate [GetDelegateForFunctionPointer](./getdelegateforfunctionpointer/)(IntPtr) | Μετατρέπει έναν μη διαχειριζόμενο δείκτη συνάρτησης σε delegate ενός συγκεκριμένου τύπου. |
| static **int32_t** [GetHRForException](./gethrforexception/)(const [System::Exception](../../system/exception/)\&) | Ανακτά το HResult από την εξαίρεση. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr) | Δημιουργεί ένα διαχειριζόμενο [String](../../system/string/) από μια μη διαχειριζόμενη UTF8-συμβολοσειρά λήξης μηδέν. |
| static [String](../../system/string/) [PtrToStringAnsi](./ptrtostringansi/)(IntPtr, int) | Δημιουργεί ένα διαχειριζόμενο [String](../../system/string/) από μια μη διαχειριζόμενη UTF8-συμβολοσειρά. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr) | Δημιουργεί ένα διαχειριζόμενο [String](../../system/string/) από μια μη διαχειριζόμενη συμβολοσειρά λήξης μηδέν. |
| static [String](../../system/string/) [PtrToStringAuto](./ptrtostringauto/)(IntPtr, int) | Δημιουργεί ένα διαχειριζόμενο [String](../../system/string/) από μια μη διαχειριζόμενη συμβολοσειρά. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr) | Δημιουργεί ένα διαχειριζόμενο [String](../../system/string/) από μια μη διαχειριζόμενη Unicode-συμβολοσειρά λήξης μηδέν. |
| static [String](../../system/string/) [PtrToStringUni](./ptrtostringuni/)(IntPtr, int) | Δημιουργεί ένα διαχειριζόμενο [String](../../system/string/) από μια μη διαχειριζόμενη Unicode-συμβολοσειρά. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr) | Δημιουργεί ένα διαχειριζόμενο [String](../../system/string/) από μια μη διαχειριζόμενη UTF8-συμβολοσειρά λήξης μηδέν. |
| static [String](../../system/string/) [PtrToStringUTF8](./ptrtostringutf8/)(IntPtr, int) | Δημιουργεί ένα διαχειριζόμενο [String](../../system/string/) από μια μη διαχειριζόμενη UTF8-συμβολοσειρά. |
| static **uint8_t** [ReadByte](./readbyte/)(IntPtr, int) | Διαβάζει byte από τη μνήμη. |
| static **int16_t** [ReadInt16](./readint16/)(IntPtr, int) | Διαβάζει short από τη μνήμη. |
| static **int32_t** [ReadInt32](./readint32/)(IntPtr, int) | Διαβάζει int από τη μνήμη. |
| static IntPtr [ReadIntPtr](./readintptr/)(IntPtr, int) | Διαβάζει IntPtr από τη μνήμη. |
| static IntPtr [SecureStringToGlobalAllocAnsi](./securestringtoglobalallocansi/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Αντιγράφει τα περιεχόμενα της καθορισμένης ασφαλούς συμβολοσειράς στη μη διαχειριζόμενη μνήμη, μετατρέποντάς τα σε μορφή ANSI. |
| static IntPtr [SecureStringToGlobalAllocUnicode](./securestringtoglobalallocunicode/)(const [SharedPtr](../../system/sharedptr/)\<[Security::SecureString](../../system.security/securestring/)\>\&) | Αντιγράφει τα περιεχόμενα της καθορισμένης ασφαλούς συμβολοσειράς στη μη διαχειριζόμενη μνήμη. |
| static IntPtr [StringToHGlobalAnsi](./stringtohglobalansi/)(const [String](../../system/string/)\&) | Αντιγράφει τα περιεχόμενα μιας καθορισμένης συμβολοσειράς στη μη διαχειριζόμενη μνήμη. |
| static IntPtr [StringToHGlobalAuto](./stringtohglobalauto/)(const [String](../../system/string/)\&) | Αντιγράφει τα περιεχόμενα μιας καθορισμένης συμβολοσειράς στη μη διαχειριζόμενη μνήμη, μετατρέποντας σε μορφή ANSI αν απαιτείται. |
| static IntPtr [StringToHGlobalUni](./stringtohglobaluni/)(const [String](../../system/string/)\&) | Αντιγράφει τα περιεχόμενα μιας καθορισμένης συμβολοσειράς στη μη διαχειριζόμενη μνήμη. |
| static void [WriteByte](./writebyte/)(IntPtr, int, **uint8_t**) | Γράφει byte στη μνήμη. |
| static void [WriteByte](./writebyte/)(IntPtr, **uint8_t**) | Γράφει byte στη μνήμη. |
| static void [WriteInt16](./writeint16/)(IntPtr, int, **int16_t**) | Γράφει short στη μνήμη. |
| static void [WriteInt32](./writeint32/)(IntPtr, int, **int32_t**) | Γράφει int στη μνήμη. |
| static void [WriteInt64](./writeint64/)(IntPtr, int, **int64_t**) | Γράφει long στη μνήμη. |
| static void [WriteIntPtr](./writeintptr/)(IntPtr, int, IntPtr) | Γράφει IntPtr στη μνήμη. |
| static void [ZeroFreeGlobalAllocAnsi](./zerofreeglobalallocansi/)(IntPtr) | Ελευθερώνει μη διαχειριζόμενο δείκτη συμβολοσειράς που έχει κατανεμηθεί χρησιμοποιώντας τη μέθοδο SecureStringToGlobalAllocAnsi. |
| static void [ZeroFreeGlobalAllocUnicode](./zerofreeglobalallocunicode/)(IntPtr) | Ελευθερώνει μη διαχειριζόμενο δείκτη συμβολοσειράς που έχει κατανεμηθεί χρησιμοποιώντας τη μέθοδο SecureStringToGlobalAllocUnicode. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Runtime::InteropServices](../)
* Βιβλιοθήκη [Aspose.Slides](../../)