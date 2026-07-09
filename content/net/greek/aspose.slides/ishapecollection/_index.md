---
title: IShapeCollection
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αντιπροσωπεύει μια συλλογή σχημάτων.
type: docs
weight: 6980
url: /el/aspose.slides/ishapecollection/
---
## IShapeCollection διεπαφή

Represents a collection of shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Λαμβάνει το αντικείμενο σχήματος γονικής ομάδας για τη συλλογή σχήματος. Μόνο για ανάγνωση [`IGroupShape`](../igroupshape). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχήματος χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχήματος. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχήματος, προαιρετικά αρχικοποιώντας το με προεπιλεγμένη μορφοποίηση προτύπου. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχήματος. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του πρωτότυπου. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχήματος. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Δημιουργεί ένα νέο σχήμα σύνδεσης με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το προσθέτει στο τέλος της συλλογής σχήματος, προαιρετικά εφαρμόζοντας το προεπιλεγμένο στυλ προτύπου. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχήματος. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να χωρά όλα τα σχήματα που προστίθενται. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχήματος. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα ορθογωνίου για την φιλοξενία μαθηματικού περιεχομένου και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Δημιουργεί ένα νέο πίνακα και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχήματος. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Αφαιρεί όλα τα σχήματα από τη συλλογή σχήματος. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Επιστρέφει τον μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με κομμάτι CD και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη, εφαρμόζοντας προεπιλεγμένη μορφοποίηση προτύπου. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη, προαιρετικά αρχικοποιώντας το με προεπιλεγμένο στυλ προτύπου. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του πρωτότυπου. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη, εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να χωρά όλα τα σχήματα που προστίθενται. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Δημιουργεί ένα νέο πίνακα και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχήματος. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Αφαιρεί το σχήμα στον καθορισμένο δείκτη από τη συλλογή σχήματος. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχήματος. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Μετακινεί τα καθορισμένα σχήματα εντός της συλλογής σχήματος, τοποθετώντας τα ξεκινώντας από τον δοσμένο δείκτη. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στο καθορισμένο εύρος. |

### Δείτε επίσης

* διεπαφή [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* διεπαφή [IShape](../ishape)
* χώρος ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->