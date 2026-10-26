---
title: ShapeCollection
second_title: Αναφορά API Aspose.Sildes για .NET
description: Αναπαριστά μια συλλογή σχημάτων.
type: docs
weight: 9860
url: /el/aspose.slides/shapecollection/
---
## ShapeCollection κλάση

Αναπαριστά μια συλλογή σχημάτων.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Ιδιότητες

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Αποκτά τον αριθμό των στοιχείων που περιλαμβάνονται στην συλλογή. Μόνο για ανάγνωση Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Επιστρέφει μια τιμή που υποδεικνύει αν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Αποκτά το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Αποκτά το αντικείμενο γονέα της ομάδας σχήματος για τη συλλογή σχημάτων. Μόνο για ανάγνωση [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object. |

## Μέθοδοι

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά αρχικοποιώντας το με προεπιλεγμένη μορφοποίηση προτύπου. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Δημιουργεί αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Δημιουργεί αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Δημιουργεί αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Δημιουργεί ένα νέο σχήμα σύνδεσης με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά εφαρμόζοντας το προεπιλεγμένο στυλ προτύπου. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να ταιριάζει με οποιαδήποτε σχήματα προστεθούν. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει το καθορισμένο SVG εικόνα σε ξεχωριστά σχήματα, και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Δημιουργεί ένα νέο αυτόματο ορθογώνιο σχήμα για τη φιλοξενία μαθηματικού περιεχομένου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στη συλλογή σχημάτων. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στη συλλογή σχημάτων. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στη συλλογή σχημάτων. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στη συλλογή σχημάτων. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προκαθορισμένη εικόνα και το προσθέτει στη συλλογή σχημάτων. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στη συλλογή σχημάτων. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στη συλλογή σχημάτων. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Δημιουργεί έναν νέο πίνακα και το προσθέτει στη συλλογή σχημάτων. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στη συλλογή σχημάτων. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στη συλλογή σχημάτων. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στη συλλογή σχημάτων. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στη συλλογή σχημάτων. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Αφαιρεί όλα τα σχήματα από τη συλλογή σχημάτων. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Επιστρέφει έναν απαριθμητή που διατρέχει τη συλλογή. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Επιστρέφει τον μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά αρχικοποιώντας το με προεπιλεγμένο στυλ προτύπου. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Δημιουργεί αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Δημιουργεί αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Δημιουργεί αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας το προεπιλεγμένο στυλ προτύπου. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά εφαρμόζοντας το προεπιλεγμένο στυλ προτύπου. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να ταιριάζει με οποιαδήποτε σχήματα προστεθούν. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προκαθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Δημιουργεί έναν νέο πίνακα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Zoom με προκαθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Αφαιρεί το σχήμα στη συγκεκριμένη θέση από τη συλλογή σχημάτων. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Μετακινεί τα καθορισμένα σχήματα μέσα στη συλλογή σχημάτων, τοποθετώντας τα από τον δοσμένο δείκτη. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στο καθορισμένο εύρος. |

### Δείτε επίσης

* κλάση [DomObject&lt;TParent&gt;](../domobject-1)
* κλάση [GroupShape](../groupshape)
* διασύνδεση [IShapeCollection](../ishapecollection)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->