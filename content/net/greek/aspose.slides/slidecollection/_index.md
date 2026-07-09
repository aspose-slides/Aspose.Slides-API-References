---
title: SlideCollection
second_title: Aspose.Sildes για .NET API Reference
description: Αντιπροσωπεύει μια συλλογή διαφανειών.
type: docs
weight: 9970
url: /el/aspose.slides/slidecollection/
---
## SlideCollection κλάση

Αντιπροσωπεύει μια συλλογή διαφανειών.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Λαμβάνει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. Μόνο για ανάγνωση Int32. |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση Boolean. |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [`Slide`](../slide). |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της συλλογής. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης διαφάνειας στο τέλος της καθορισμένης ενότητας. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης πηγής διαφάνειας στο τέλος της συλλογής. Η κατάλληλη διάταξη θα επιλεχθεί αυτόματα από το καθορισμένο master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Type ή Name όπως η διάταξη της πηγής διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη, τότε η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (εάν το allowCloneMissingLayout είναι true) ή θα προκληθεί PptxEditException (εάν το allowCloneMissingLayout είναι false). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Προσθέτει μια νέα κενή διαφάνεια στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Δημιουργεί διαφάνειες από το έγγραφο PDF και τις προσθέτει στο τέλος της συλλογής λαμβάνοντας υπόψη τις επιλογές εισαγωγής PDF. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Επιστρέφει έναν δείκτη της καθορισμένης διαφάνειας στη συλλογή. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης πηγής διαφάνειας στη συγκεκριμένη θέση της συλλογής. Η κατάλληλη διάταξη θα επιλεχθεί αυτόματα από το καθορισμένο master (η κατάλληλη διάταξη είναι η διάταξη με τον ίδιο Type ή Name όπως η διάταξη της πηγής διαφάνειας). Εάν δεν υπάρχει κατάλληλη διάταξη, τότε η διάταξη της πηγής διαφάνειας θα κλωνοποιηθεί (εάν το allowCloneMissingLayout είναι true) ή θα προκληθεί PptxEditException (εάν το allowCloneMissingLayout είναι false). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Εισάγει ένα αντίγραφο μιας καθορισμένης διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Δημιουργεί διαφάνειες από κείμενο HTML και τις εισάγει στη συλλογή στη συγκεκριμένη θέση. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Μετακινεί τη διαφάνεια από τη συλλογή στη συγκεκριμένη θέση. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Μετακινεί διαφάνειες από τη συλλογή στη συγκεκριμένη θέση. Οι διαφάνειες θα τοποθετηθούν ξεκινώντας από το δείκτη με τη σειρά που εμφανίζονται στη λίστα. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις διαφάνειες από το καθορισμένο εύρος. Δείκτης της πρώτης διαφάνειας προς προσθήκη. Αριθμός διαφανειών προς προσθήκη. |

### Δείτε επίσης

* κλάση [DomObject&lt;TParent&gt;](../domobject-1)
* κλάση [Presentation](../presentation)
* διασύνδεση [ISlideCollection](../islidecollection)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->