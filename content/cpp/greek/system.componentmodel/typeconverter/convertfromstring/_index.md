---
title: ConvertFromString()
second_title: Aspose.Slides για την Αναφορά API C++
description: Μετατρέπει τη συμβολοσειρά σε αντικείμενο.
type: docs
weight: 40
url: /el/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) μέθοδος

Μετατρέπει συμβολοσειρά σε αντικείμενο.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Τιμή προς μετατροπή. |

### Τιμή Επιστροφής

μετατρεπόμενο αντικείμενο.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) μέθοδος

Μετατρέπει συμβολοσειρά σε αντικείμενο.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) πληροφορίες περιβάλλοντος μετατροπής. |
| text | const [System::String](../../../system/string/)\& | Τιμή προς μετατροπή. |

### Τιμή Επιστροφής

μετατρεπόμενο αντικείμενο.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) μέθοδος

Μετατρέπει συμβολοσειρά σε αντικείμενο.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) πληροφορίες περιβάλλοντος μετατροπής. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Πολιτισμός που θα χρησιμοποιηθεί κατά τη μετατροπή αντικειμένων. |
| text | const [System::String](../../../system/string/)\& | Τιμή προς μετατροπή. |

### Τιμή Επιστροφής

μετατρεπόμενο αντικείμενο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [String](../../../system/string/)
* Κλάση [TypeConverter](../)
* Κλάση [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Χώρος ονομάτων [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)