---
title: Parse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα "box" για την τιμή του σταθερού αρίθμησης της καθορισμένης αρίθμησης με το καθορισμένο όνομα. Μία παράμετρος καθορίζει αν η διάκριση πεζών-κεφαλαίων πρέπει να αγνοηθεί κατά την ερμηνεία της συμβολοσειράς που καθορίζει το όνομα του σταθερού αρίθμησης.
type: docs
weight: 53
url: /el/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) μέθοδος

Δημιουργεί ένα "box" για την τιμή του σταθερού αρίθμησης της καθορισμένης αρίθμησης με το καθορισμένο όνομα. Μία παράμετρος καθορίζει αν η διάκριση πεζών-κεφαλαίων πρέπει να αγνοηθεί κατά την ερμηνεία της συμβολοσειράς που καθορίζει το όνομα του σταθερού αρίθμησης.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Παραμέτρων

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Καθορίζει τον τύπο της αρίθμησης |
| str | const [String](../../string/)\& | Το όνομα του σταθερού αρίθμησης, της τιμής του οποίου θα δημιουργηθεί box |
| ignoreCase | **bool** | Καθορίζει αν η διάκριση πεζών-κεφαλαίων πρέπει να αγνοηθεί κατά την ερμηνεία της συμβολοσειράς που αντιπροσωπεύει το όνομα του σταθερού αρίθμησης |

### Τιμή Επιστροφής

Ένα shared pointer στο αντικείμενο που αντιπροσωπεύει την boxed τιμή του καθορισμένου σταθερού αρίθμησης

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) μέθοδος

Δημιουργεί ένα "box" για την τιμή του σταθερού αρίθμησης της καθορισμένης αρίθμησης με το καθορισμένο όνομα.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Παραμέτρων

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Καθορίζει τον τύπο της αρίθμησης |
| str | const [String](../../string/)\& | Το όνομα του σταθερού αρίθμησης, της τιμής του οποίου θα δημιουργηθεί box |

### Τιμή Επιστροφής

Ένα shared pointer στο αντικείμενο που αντιπροσωπεύει την boxed τιμή του καθορισμένου σταθερού αρίθμησης

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [Object](../../object/)
* Κλάση [TypeInfo](../../typeinfo/)
* Κλάση [String](../../string/)
* Κλάση [BoxedValueBase](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)