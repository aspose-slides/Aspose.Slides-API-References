---
title: DataSourceTypeForErrorBarsCustomValues
second_title: Aspose.Slides για C++ Αναφορά API
description: "Καθορίζει τύπους τιμών στη λίστα ιδιοτήτων ChartDataPoint::get_ErrorBarsCustomValues"
type: docs
weight: 404
url: /el/aspose.slides.charts/datasourcetypeforerrorbarscustomvalues/
---
## DataSourceTypeForErrorBarsCustomValues κλάση

Καθορίζει τύπους τιμών στη λίστα ιδιοτήτων [ChartDataPoint::get_ErrorBarsCustomValues](../chartdatapoint/get_errorbarscustomvalues/)

```cpp
class DataSourceTypeForErrorBarsCustomValues : public Aspose::Slides::Charts::IDataSourceTypeForErrorBarsCustomValues
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues/)() |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, αν και σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα, αν και σύμφωνα με το IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() override | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι η ενεργή σε αντικείμενο ιδιότητας XMinus των σημείων δεδομένων για προσαρμοσμένες τιμές σφαλμάτων. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας ChartDataPoint.ErrorBarsCustomValues.XMinus.Data. Διαβάστε [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() override | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι η ενεργή σε αντικείμενο ιδιότητας XPlus των σημείων δεδομένων για προσαρμοσμένες τιμές σφαλμάτων. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας ChartDataPoint.ErrorBarsCustomValues.XPlus.Data. Διαβάστε [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() override | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι η ενεργή σε αντικείμενο ιδιότητας YMinus των σημείων δεδομένων για προσαρμοσμένες τιμές σφαλμάτων. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data. Διαβάστε [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() override | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι η ενεργή σε αντικείμενο ιδιότητας YPlus των σημείων δεδομένων για προσαρμοσμένες τιμές σφαλμάτων. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data. Διαβάστε [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Λαμβάνει τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Αναλογική της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Ενεργοποιεί το hashing προσαρμοσμένων αντικειμένων. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Λαμβάνει τον πραγματικό τύπο του αντικειμένου. Αναλογική κλήση της C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει αν το αντικείμενο αντιπροσωπεύει μια παρουσία τύπου που περιγράφεται από targetType. Αναλογικό του τελεστή 'is' της C#. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το statement lock() της C#. Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Αναλογική της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ενεργοποιεί την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί το αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηγοριών μέσω copy constructing. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Στην πραγματικότητα δεν αντιγράφει τίποτα, απλώς αρχικοποιεί νέο αντικείμενο και επιτρέπει τη δημιουργία υποκατηγοριών μέσω copy constructing. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά ενός αντικειμένου τύπου τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδικοποίηση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινής αναφοράς κατά την καθορισμένη τιμή. |
| void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) override | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι η ενεργή σε αντικείμενο ιδιότητας XMinus των σημείων δεδομένων για προσαρμοσμένες τιμές σφαλμάτων. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας ChartDataPoint.ErrorBarsCustomValues.XMinus.Data. Γράψτε [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) override | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι η ενεργή σε αντικείμενο ιδιότητας XPlus των σημείων δεδομένων για προσαρμοσμένες τιμές σφαλμάτων. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας ChartDataPoint.ErrorBarsCustomValues.XPlus.Data. Γράψτε [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) override | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι η ενεργή σε αντικείμενο ιδιότητας YMinus των σημείων δεδομένων για προσαρμοσμένες τιμές σφαλμάτων. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data. Γράψτε [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) override | Καθορίζει αν η ιδιότητα AsCell ή AsLiteralString ή AsLiteralDouble είναι η ενεργή σε αντικείμενο ιδιότητας YPlus των σημείων δεδομένων για προσαρμοσμένες τιμές σφαλμάτων. Με άλλα λόγια καθορίζει τον τύπο τιμής της ιδιότητας ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data. Γράψτε [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίζει το n'th όρισμα προτύπου ως αδύναμο δείκτη (αντί για κοινό). Επιτρέπει την αλλαγή δεικτών σε containers σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Λαμβάνει την τρέχουσα τιμή του μετρητή κοινής αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινής αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Αναλογική της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Ενεργοποιεί τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το construct typeof([System.Object](../../system/object/)) της C#. |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το statement lock() της C# για ξεκλείδωμα. Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον μετρητή αδύναμης αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον μετρητή αδύναμης αναφοράς. Δεν θα πρέπει να κληθεί απευθείας· αντί αυτού, χρησιμοποιήστε έξυπνους δείκτες ή ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Απελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [IDataSourceTypeForErrorBarsCustomValues](../idatasourcetypeforerrorbarscustomvalues/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)