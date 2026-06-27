---
title: IShapeCollection
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει μια συλλογή σχημάτων.
type: docs
weight: 6960
url: /el/aspose.slides/ishapecollection/
---
## IShapeCollection διασύνδεση

Αντιπροσωπεύει μια συλλογή σχήματος.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Παίρνει το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Παίρνει το αντικείμενο του γονικού group shape για τη συλλογή shapes. Μόνο για ανάγνωση [`IGroupShape`](../igroupshape). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με ένα κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά αρχικοποιώντας το με την προεπιλεγμένη μορφοποίηση προτύπου. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Δημιουργεί ένα νέο σχήμα σύνδεσμου με προεπιλεγμένο στιλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά εφαρμόζοντας το προεπιλεγμένο στιλ προτύπου. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να χωρά όλα τα σχήματα που προστίθενται σε αυτήν. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Δημιουργεί ένα νέο αυτόματο ορθογώνιο σχήμα για τη φιλοξενία μαθηματικού περιεχομένου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Δημιουργεί έναν νέο πίνακα και τον προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Αφαιρεί όλα τα σχήματα από τη συλλογή σχημάτων. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Επιστρέφει το μηδενικό-βάση δείκτη της πρώτης εμφάνισης του συγκεκριμένου σχήματος στη συλλογή. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με ένα κομμάτι CD και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά αρχικοποιώντας το με το προεπιλεγμένο στιλ προτύπου. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας το προεπιλεγμένο στιλ προτύπου. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά εφαρμόζοντας το προεπιλεγμένο στιλ προτύπου. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να χωρά όλα τα σχήματα που προστίθενται σε αυτήν. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Δημιουργεί ένα νέο πίνακα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Zoom με προορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Αφαιρεί την πρώτη εμφάνιση του συγκεκριμένου σχήματος από τη συλλογή σχημάτων. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Αφαιρεί το σχήμα στη συγκεκριμένη θέση από τη συλλογή σχημάτων. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Μετακινεί το συγκεκριμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Μετακινεί τα συγκεκριμένα σχήματα στη συλλογή σχημάτων, τοποθετώντας τα ξεκινώντας από τον δοσμένο δείκτη. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στο καθορισμένο εύρος. |

### Δείτε επίσης

* διασύνδεση [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* διασύνδεση [IShape](../ishape)
* χωροδιάστημα [Aspose.Slides](../../aspose.slides)
* σύγκροτο [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->