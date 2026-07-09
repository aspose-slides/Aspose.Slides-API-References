---
title: ISlideCollection
second_title: Aspose.Sildes για .NET API Reference
description: Αναπαριστά μια συλλογή διαφανειών.
type: docs
weight: 7050
url: /el/aspose.slides/islidecollection/
---
## ISlideCollection διεπαφή

Αναπαριστά μια συλλογή διαφανειών.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Παίρνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [`ISlide`](../islide). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της καθορισμένης ενότητας. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης πηγής διαφάνειας στο τέλος της συλλογής. Το κατάλληλο layout θα επιλεγεί αυτόματα από το καθορισμένο master (το κατάλληλο layout είναι το layout με τον ίδιο Type ή Name όπως το layout της πηγής διαφάνειας). Εάν δεν υπάρχει κατάλληλο layout, τότε το layout της πηγής διαφάνειας θα κλωνοποιηθεί (αν το allowCloneMissingLayout είναι true) ή θα προκληθεί PptxEditException (αν το allowCloneMissingLayout είναι false). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Προσθέτει μια νέα κενή διαφάνεια στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής λαμβάνοντας υπόψη τις επιλογές εισαγωγής PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Επιστρέφει ένα δείκτη της καθορισμένης διαφάνειας στη συλλογή. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης πηγής διαφάνειας στη συγκεκριμένη θέση της συλλογής. Το κατάλληλο layout θα επιλεγεί αυτόματα από το καθορισμένο master (το κατάλληλο layout είναι το layout με τον ίδιο Type ή Name όπως το layout της πηγής διαφάνειας). Εάν δεν υπάρχει κατάλληλο layout, τότε το layout της πηγής διαφάνειας θα κλωνοποιηθεί (αν το allowCloneMissingLayout είναι true) ή θα προκληθεί PptxEditException (αν το allowCloneMissingLayout είναι false). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Μετακινεί τη διαφάνεια από τη συλλογή στη συγκεκριμένη θέση. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Μετακινεί διαφάνειες από τη συλλογή στη συγκεκριμένη θέση. Οι διαφάνειες θα τοποθετηθούν ξεκινώντας από τον δείκτη με τη σειρά που εμφανίζονται στη λίστα. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες από το καθορισμένο εύρος. |

### Δείτε επίσης

* διεπαφή [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* διεπαφή [ISlide](../islide)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->