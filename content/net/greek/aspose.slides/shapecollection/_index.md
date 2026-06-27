---
title: ShapeCollection
second_title: Aspose.Sildes για .NET Αναφορά API
description: Αναπαριστά μια συλλογή από σχήματα.
type: docs
weight: 9840
url: /el/aspose.slides/shapecollection/
---
## ShapeCollection κλάση

Αναπαριστά μια συλλογή από σχήματα.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Ιδιότητες

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Επιστρέφει τον αριθμό των στοιχείων που περιέχονται στην συλλογή. Μόνο για ανάγνωση Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (ασφαλής σε νήματα). Μόνο για ανάγνωση Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Επιστρέφει το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Επιστρέφει το αντικείμενο γονικού group shape για τη συλλογή σ shapes. Μόνο για ανάγνωση [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Επιστρέφει τη ρίζα συγχρονισμού. Μόνο για ανάγνωση Object. |

## Μέθοδοι

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με κομμάτι CD και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σ shapes χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σ shapes. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σ shape με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο αυτόματο σ shape και το προσθέτει στο τέλος της συλλογής σ shapes, προαιρετικά αρχικοποιώντας το με προεπιλεγμένη μορφοποίηση προτύπου. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα σειράς δεδομένων και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα σειράς δεδομένων και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Δημιουργεί αντίγραφο του καθορισμένου σ shape και το προσθέτει στο τέλος της συλλογής σ shapes. Το κλωνοποιημένο σ shape διατηρεί τη θέση και το μέγεθος του αρχικού. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Δημιουργεί αντίγραφο του καθορισμένου σ shape και το προσθέτει στο τέλος της συλλογής σ shapes. Το νέο σ shape διατηρεί το πλάτος και το ύψος του *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Δημιουργεί αντίγραφο του καθορισμένου σ shape και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Δημιουργεί ένα νέο connector σ shape με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο connector σ shape και το προσθέτει στο τέλος της συλλογής σ shapes, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Δημιουργεί ένα νέο κενό group σ shape και το προσθέτει στο τέλος της συλλογής σ shapes. Το πλαίσιο της ομάδας προσαρμόζεται αυτόματα ώστε να περιλαμβάνει τυχόν σ shapes που προστίθενται. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Δημιουργεί ένα νέο group σ shape, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σ shapes και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σ shapes. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σ shape τύπου rectangle για μαθηματικό περιεχόμενο και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Δημιουργεί ένα νέο πίνακα και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σ shapes. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Αφαιρεί όλα τα σ shapes από τη συλλογή σ shapes. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Αντιγράφει όλα τα στοιχεία της συλλογής στον καθορισμένο πίνακα. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Επιστρέφει έναν ενομετρητή που διατρέχει τη συλλογή. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Επιστρέφει τον μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου σ shape στη συλλογή. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σ shape και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται, εφαρμόζοντας προεπιλεγμένη μορφοποίηση προτύπου. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο αυτόματο σ shape και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται, προαιρετικά αρχικοποιώντας το με προεπιλεγμένο στυλ προτύπου. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα σειράς δεδομένων και ρυθμίσεων, και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα σειράς δεδομένων και ρυθμίσεων, και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Δημιουργεί αντίγραφο του καθορισμένου σ shape και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. Το κλωνοποιημένο σ shape διατηρεί τη θέση και το μέγεθος του αρχικού. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Δημιουργεί αντίγραφο του καθορισμένου σ shape και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. Το νέο σ shape διατηρεί το πλάτος και το ύψος του *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Δημιουργεί αντίγραφο του καθορισμένου σ shape και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Δημιουργεί ένα νέο connector σ shape και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται, εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Δημιουργεί ένα νέο connector σ shape και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Δημιουργεί ένα νέο κενό group σ shape και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. Το πλαίσιο της ομάδας προσαρμόζεται αυτόματα ώστε να περιλαμβάνει τυχόν σ shapes που προστίθενται. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Δημιουργεί ένα νέο πίνακα και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Δημιουργεί ένα νέο πλαίσιο Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σ shapes στη θέση που υποδεικνύεται. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σ shape από τη συλλογή σ shapes. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Αφαιρεί το σ shape στη θέση που υποδεικνύεται από τη συλλογή σ shapes. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Μετακινεί το καθορισμένο σ shape σε νέα θέση μέσα στη συλλογή σ shapes. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Μετακινεί τα καθορισμένα σ shapes μέσα στη συλλογή σ shapes, τοποθετώντας τα ξεκινώντας από τον δοθέντα δείκτη. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σ shapes. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σ shapes στο καθορισμένο εύρος. |

### Δείτε επίσης

* κλάση [DomObject&lt;TParent&gt;](../domobject-1)
* κλάση [GroupShape](../groupshape)
* διεπαφή [IShapeCollection](../ishapecollection)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συναρμολόγηση [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->