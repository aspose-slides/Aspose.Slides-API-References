---
title: ConvertTo()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει το αντικείμενο σε συγκεκριμένο τύπο.
type: docs
weight: 53
url: /el/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) μέθοδος


Μετατρέπει το αντικείμενο σε συγκεκριμένο τύπο.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


### Παράμετρα

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) για μετατροπή. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Τύπος στον οποίο θα μετατραπεί. |

### Τιμή Επιστροφής

Μετατραπεί αντικείμενο.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) μέθοδος


Μετατρέπει το αντικείμενο σε συγκεκριμένο τύπο.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


### Παράμετρα

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) πληροφορίες περιβάλλοντος μετατροπής. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Πολιτισμός που θα χρησιμοποιηθεί κατά τη μετατροπή αντικειμένων. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) για μετατροπή. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Τύπος στον οποίο θα μετατραπεί. |

### Τιμή Επιστροφής

Μετατραπεί αντικείμενο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [TypeConverter](../)
* Κλάση [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Χώρος ονομάτων [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)