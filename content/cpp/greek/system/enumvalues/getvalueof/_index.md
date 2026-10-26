---
title: GetValueOf()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει τη συσκευασμένη τιμή της σταθεράς enum με το συγκεκριμένο όνομα.
type: docs
weight: 53
url: /el/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const μέθοδος

Επιστρέφει μια συσκευασμένη τιμή της σταθεράς enum με το συγκεκριμένο όνομα.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | Το όνομα της σταθεράς enum |
| ignoreCase | **bool** | Καθορίζει εάν πρέπει να αγνοηθεί η διάκριση πεζών-κεφαλαίων κατά την ερμηνεία του ονόματος της σταθεράς enum |

### Τιμή Επιστροφής

Μια συσκευασμένη τιμή της σταθεράς enum της οποίας το όνομα έχει καθοριστεί στο **str**.

## EnumValues::GetValueOf(long) const μέθοδος

Επιστρέφει μια συσκευασμένη τιμή της σταθεράς enum με τη συγκεκριμένη τιμή.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| val | long | Η τιμή της σταθεράς enum |

### Τιμή Επιστροφής

Μια συσκευασμένη τιμή της σταθεράς enum της οποίας η τιμή έχει καθοριστεί στο **str**.

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../../string/)
* Class [EnumValues](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)