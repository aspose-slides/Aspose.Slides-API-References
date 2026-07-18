---
title: String()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προεπιλεγμένος κατασκευαστής. Δημιουργεί αντικείμενο string που θεωρείται null.
type: docs
weight: 14
url: /el/system/string/string/
---
## String::String() κατασκευαστής

Προεπιλεγμένος κατασκευαστής. Δημιουργεί αντικείμενο string που θεωρείται null.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) κατασκευαστής

Δημιουργεί string βάσει κυριολεκτικού string. Θεωρεί το κυριολεκτικό ως συμβολοσειρά τελειωμένη με null και υπολογίζει το μήκος της στόχου με βάση το μέγεθος του κυριολεκτικού.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | T\& | [String](../) δείκτης κυριολεκτικού. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) κατασκευαστής

Δημιουργεί string βάσει δείκτη συμβολοσειράς χαρακτήρων. Θεωρεί τη συμβολοσειρά ως τελειωμένη με null και υπολογίζει το μήκος της στόχου με βάση τον χαρακτήρα null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | Δείκτης συμβολοσειράς χαρακτήρων. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) κατασκευαστής

Δημιουργεί string βάσει κυριολεκτικού string. Θεωρεί το κυριολεκτικό ως συμβολοσειρά τελειωμένη με null σε UTF-8 και υπολογίζει το μήκος της στόχου με βάση το μέγεθος του κυριολεκτικού.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | T\& | [String](../) δείκτης κυριολεκτικού. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) κατασκευαστής

Δημιουργεί string βάσει δείκτη συμβολοσειράς χαρακτήρων. Θεωρεί τη συμβολοσειρά ως τελειωμένη με null σε UTF-8 και υπολογίζει το μήκος της στόχου με βάση τον χαρακτήρα null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | Δείκτης συμβολοσειράς χαρακτήρων. |

## String::String(const char16_t *, int) κατασκευαστής

Δημιουργεί string από δείκτη συμβολοσειράς χαρακτήρων και ρητό μήκος.

```cpp
System::String::String(const char16_t *str, int length)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const char16_t * | [String](../) δείκτης, μπορεί να είναι κυριολεκτικό ή πίνακας. |
| length | int | Ρητό μήκος συμβολοσειράς |

## String::String(const ReadOnlySpan\<char16_t\>\&) κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [System.String](../) με τους Unicode χαρακτήρες που υποδεικνύονται στο καθορισμένο read-only span.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Ένα read-only span Unicode χαρακτήρων. |

## String::String(const char *, int) κατασκευαστής

Δημιουργεί string από δείκτη συμβολοσειράς χαρακτήρων και ρητό μήκος.

```cpp
System::String::String(const char *str, int length)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const char * | [String](../) δείκτης στα δεδομένα UTF-8, μπορεί να είναι κυριολεκτικό ή πίνακας. |
| length | int | Ρητό μήκος συμβολοσειράς |

## String::String(const char16_t *, int, int) κατασκευαστής

Δημιουργεί string από δείκτη συμβολοσειράς χαρακτήρων ξεκινώντας από τη θέση εκκίνησης με το δοσμένο μήκος.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const char16_t * | [String](../) δείκτης, μπορεί να είναι κυριολεκτικό ή πίνακας. |
| start | int | Θέση εκκίνησης. |
| length | int | [String](../) μήκος. |

## String::String(const char16_t, int) κατασκευαστής

Κατασκευαστής γεμίσματος.

```cpp
System::String::String(const char16_t ch, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ch | const char16_t | Χαρακτήρας γεμίσματος. |
| count | int | Μήκος στόχου. |

## String::String(T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) κατασκευαστής

Κατασκευαστής nullptr. Ορίζεται ως πρότυπο για την επίλυση προτεραιοτήτων με άλλους προτύπους κατασκευαστές.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Πρέπει να είναι nullptr_t |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) κατασκευαστής

Δημιουργεί string βάσει κυριολεκτικού ευρείας συμβολοσειράς. Θεωρεί το κυριολεκτικό ως συμβολοσειρά τελειωμένη με null και υπολογίζει το μήκος της στόχου με βάση το μέγεθος του κυριολεκτικού. Η μετατροπή από **wchar_t** είναι χρονοβόρα σε ορισμένες πλατφόρμες, επομένως δεν επιτρέπονται σιωπές μετατροπές.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | T\& | [String](../) δείκτης κυριολεκτικού. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) κατασκευαστής

Δημιουργεί string βάσει δείκτη ευρείας συμβολοσειράς χαρακτήρων. Θεωρεί τη συμβολοσειρά ως τελειωμένη με null και υπολογίζει το μήκος της στόχου με βάση τον χαρακτήρα null. Η μετατροπή από **wchar_t** είναι χρονοβόρα σε ορισμένες πλατφόρμες, επομένως δεν επιτρέπονται σιωπές μετατροπές.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const T\& | Δείκτης συμβολοσειράς χαρακτήρων. |

## String::String(const wchar_t *, int) κατασκευαστής

Δημιουργεί string από δείκτη ευρείας συμβολοσειράς χαρακτήρων και ρητό μήκος. Η μετατροπή από **wchar_t** είναι χρονοβόρα σε ορισμένες πλατφόρμες, επομένως δεν επιτρέπονται σιωπές μετατροπές.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) δείκτης, μπορεί να είναι κυριολεκτικό ή πίνακας. |
| length | int | Ρητό μήκος συμβολοσειράς |

## String::String(const wchar_t, int) κατασκευαστής

Κατασκευαστής γεμίσματος. Η μετατροπή από **wchar_t** είναι χρονοβόρα σε ορισμένες πλατφόρμες, επομένως δεν επιτρέπονται σιωπές μετατροπές.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ch | const **wchar_t** | Χαρακτήρας γεμίσματος. |
| count | int | Μήκος στόχου. |

## String::String(const String\&) κατασκευαστής

Κατασκευαστής αντιγραφής.

```cpp
System::String::String(const String &str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) για αντιγραφή. |

## String::String(String\&&) κατασκευαστής

Κατασκευαστής μετακίνησης.

```cpp
System::String::String(String &&str) noexcept
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) για μεταφορά δεδομένων. |

## String::String(const ArrayPtr\<char16_t\>\&) κατασκευαστής

Μετατρέπει ολόκληρο τον πίνακα χαρακτήρων σε string.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) για μετατροπή σε string. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) κατασκευαστής

Μετατρέπει υπο-εύρος πίνακα χαρακτήρων σε string. Εάν οι παράμετροι είναι εκτός ορίων του πίνακα, δημιουργείται κενή συμβολοσειρά.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Πίνακας χαρακτήρων. |
| offset | int | Δείκτης εκκίνησης υπο-πίνακα. |
| len | int | Μήκος υπο-πίνακα. |

## String::String(const codeporting_icu::UnicodeString\&) κατασκευαστής

Τυλίγει το UnicodeString σε [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString για τυλίξιμο σε [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) κατασκευαστής

Κατασκευαστής μετακίνησης.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString για τυλίξιμο σε [String](../). |

## String::String(const std::wstring\&) κατασκευαστής

Δημιουργεί [String](../) από ευρείας συμβολοσειράς.

```cpp
System::String::String(const std::wstring &str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const std::wstring\& | Ευρείας συμβολοσειράς για μετατροπή σε [String](../). |

## String::String(const std::u16string\&) κατασκευαστής

Δημιουργεί [String](../) από συμβολοσειρά utf-16.

```cpp
System::String::String(const std::u16string &str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const std::u16string\& | Συμβολοσειρά Utf16 για μετατροπή σε [String](../). |

## String::String(const std::string\&) κατασκευαστής

Δημιουργεί [String](../) από std::string σε μορφή UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| utf8str | const std::string\& | std::string για μετατροπή σε [String](../). |

## String::String(const std::u32string\&) κατασκευαστής

Δημιουργεί [String](../) από std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string για μετατροπή σε [String](../). |

## Δείτε επίσης

* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [String](../)
* Κλάση [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)