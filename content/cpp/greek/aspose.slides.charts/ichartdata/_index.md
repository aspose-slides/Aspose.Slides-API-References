---
title: IChartData
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναπαριστά τα δεδομένα που χρησιμοποιούνται για τη σχεδίαση γραφήματος.
type: docs
weight: 651
url: /el/aspose.slides.charts/ichartdata/
---
## IChartData κλάση

Αναπαριστά τα δεδομένα που χρησιμοποιούνται για τη σχεδίαση γραφήματος.

```cpp
class IChartData : public virtual System::Object
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Συγκρίνει αντικείμενα χρησιμοποιώντας τη σημασιολογία C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τύπου αναφοράς σε στυλ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Συγκρίνει αντικείμενα τιμής σε στυλ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Εξομοιώνει τη σύγκριση κινητής υποδιαστολής σε στυλ C# όπου δύο NaN θεωρούνται ίσα παρόλο που σύμφωνα με IEC 60559:1989 το NaN δεν είναι ίσο με καμία τιμή, συμπεριλαμβανομένου του NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Μόνο για εσωτερική χρήση. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | Αποκτά τις κύριες κατηγορίες (ή και τις κύριες και δευτερεύουσες κατηγορίες εάν το [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) είναι ορισμένο σε false). Μόνο για ανάγνωση [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | Επιστρέφει την κύρια κατηγορία στον καθορισμένο δείκτη. Εάν το [get_UseSecondaryCategories](./get_usesecondarycategories/) είναι false, παίρνει από όλες τις κατηγορίες. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | Αποκτά το εργοστάσιο κελιών για τη δημιουργία κελιών που χρησιμοποιούνται για σειρές ή κατηγορίες γραφήματος. Μόνο για ανάγνωση [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Επιστρέφει τη σειρά στον καθορισμένο δείκτη. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | Αναπαριστά την πηγή δεδομένων του γραφήματος |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | Αποκτά τον τύπο του ενσωματωμένου βιβλίου εργασίας. Επιστρέφει [WorkbookType::NotDefined](../workbooktype/) εάν το [IChartData::get_DataSourceType](./get_datasourcetype/) είναι [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). Μόνο για ανάγνωση [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | Αναπαριστά τη διαδρομή εξωτερικού βιβλίου εργασίας εάν η πηγή δεδομένων είναι εξωτερική, αλλιώς null |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | Αποκτά τις δευτερεύουσες κατηγορίες εάν το [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) είναι true. Μόνο για ανάγνωση [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | Επιστρέφει τη δευτερεύουσα κατηγορία στον καθορισμένο δείκτη. Εάν το [get_UseSecondaryCategories](./get_usesecondarycategories/) είναι false, τότε το [IChartData::get_SecondaryCategories](./get_secondarycategories/) είναι null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | Αποκτά τις σειρές. Μόνο για ανάγνωση [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | Επιστρέφει την ομάδα των σειρών στον καθορισμένο δείκτη. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | Αποκτά τις ομάδες των σειρών. Μόνο για ανάγνωση [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | Εάν οριστεί σε false τότε το [IChartData::get_SecondaryCategories](./get_secondarycategories/) επιστρέφει null και τα δεδομένα στο [IChartData::get_Categories](./get_categories/) χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν οριστεί σε true τότε τα δεδομένα στο [IChartData::get_SecondaryCategories](./get_secondarycategories/) χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στο [IChartData::get_Categories](./get_categories/) χρησιμοποιούνται για κύριες σειρές. Ανάγνωση **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Αποκτά τη δομή δεδομένων μετρητή αναφοράς που σχετίζεται με το αντικείμενο. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Ανάλογο της μεθόδου C# [Object.GetHashCode()](../../system/object/gethashcode/). Επιτρέπει τη δημιουργία κατατεμαχίσεων προσαρμοσμένων αντικειμένων. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | Αποκτά το εύρος δεδομένων του γραφήματος. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Αποκτά τον πραγματικό τύπο του αντικειμένου. Ανάλογο της κλήσης C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ελέγχει εάν το αντικείμενο αντιπροσωπεύει μια περίπτωση τύπου που περιγράφεται από το targetType. Ανάλογο του τελεστή C# 'is'. |
| void [Lock](../../system/object/lock/)() | Υλοποιεί το κλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Ανάλογο της μεθόδου C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Επιτρέπει την κλωνοποίηση προσαρμοσμένων τύπων. |
|  [Object](../../system/object/object/)() | Δημιουργεί αντικείμενο. Αρχικοποιεί όλες τις εσωτερικές δομές δεδομένων. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Κατασκευαστής αντιγραφής. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς δημιουργεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Τελεστής ανάθεσης. Δεν αντιγράφει τίποτα, στην πραγματικότητα, απλώς δημιουργεί νέο αντικείμενο και επιτρέπει την αντιγραφή κατασκευής υποκατηγοριών. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | Γράφει το εσωτερικά περιεχόμενο βιβλίου εργασίας [Excel](../../aspose.slides.excel/) σε ροή εντός μνήμης. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Συγκρίνει αντικείμενα κατά αναφορά. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Συγκρίνει αναφορά τιμής με nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειράς και nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Ειδίκευση του [Object::ReferenceEquals](../../system/object/referenceequals/) για την περίπτωση συμβολοσειρών. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Μειώνει τον μετρητή κοινόχρηστης αναφοράς κατά την καθορισμένη τιμή. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | Εάν οριστεί σε false τότε το [IChartData::get_SecondaryCategories](./get_secondarycategories/) επιστρέφει null και τα δεδομένα στο [IChartData::get_Categories](./get_categories/) χρησιμοποιούνται τόσο για κύριες όσο και για δευτερεύουσες σειρές. Εάν οριστεί σε true τότε τα δεδομένα στο [IChartData::get_SecondaryCategories](./get_secondarycategories/) χρησιμοποιούνται για δευτερεύουσες σειρές και τα δεδομένα στο [IChartData::get_Categories](./get_categories/) χρησιμοποιούνται για κύριες σειρές. Εγγραφή **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. Τα δεδομένα [Chart](../chart/) θα ενημερώνονται από το βιβλίο εργασίας προορισμού. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | Ορίζει το εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | Ορίστε το εύρος δεδομένων του γραφήματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν με βάση το νέο εύρος δεδομένων. Εάν ο αριθμός σειρών στο εύρος δεδομένων είναι μεγαλύτερος από τον αριθμό σειρών στα δεδομένα του γραφήματος, τότε επιπλέον σειρές με τον ίδιο τύπο όπως η τελευταία σειρά στην τρέχουσα συλλογή θα προστεθούν στο τέλος της συλλογής. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ορίστε το n'tο όρισμα προτύπου σε αδύναμο δείκτη (αντί σε κοινόχρηστο). Επιτρέπει την εναλλαγή δεικτών σε συλλογές σε αδύναμη λειτουργία. |
| int [SharedCount](../../system/object/sharedcount/)() const | Αποκτά την τρέχουσα τιμή του μετρητή κοινόχρηστης αναφοράς. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Αυξάνει τον μετρητή κοινόχρηστης αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Μειώνει και επιστρέφει τον μετρητή κοινόχρηστης αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | Αντιστρέφει τα δεδομένα κατά τον άξονα. Τα δεδομένα που σχεδιάζονται στον άξονα X θα μετακινηθούν στον άξονα Y και αντίστροφα. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Ανάλογο της μεθόδου C# [Object.ToString()](../../system/object/tostring/). Επιτρέπει τη μετατροπή προσαρμοσμένων αντικειμένων σε συμβολοσειρά. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Υλοποιεί το κατασκευή C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Υλοποιεί το ξεκλείδωμα της δήλωσης C# lock(). Καλείται απευθείας ή χρησιμοποιεί το αντικείμενο φρουρού [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Αυξάνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Μειώνει τον αδύναμο μετρητή αναφοράς. Δεν πρέπει να κληθεί απευθείας· χρησιμοποιήστε έξυπνα δείκτες ή ThisProtector. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | Αρχικοποιεί το εσωτερικά περιεχόμενο βιβλίου εργασίας [Excel](../../aspose.slides.excel/) με την τιμή που καθορίζεται από τον χρήστη. |
| virtual  [~Object](../../system/object/~object/)() | Καταστρέφει το αντικείμενο. Ελευθερώνει όλες τις εσωτερικές δομές δεδομένων. |

## Δείτε επίσης

* Κλάση [Object](../../system/object/)
* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)