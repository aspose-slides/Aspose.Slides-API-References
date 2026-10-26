---
title: ShapeCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή σχημάτων.
type: docs
url: /el/com.aspose.slides/shapecollection/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Αντιπροσωπεύει μια συλλογή σχημάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [size()](#size--) | Επιστρέφει τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγματα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγματα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγματα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγματα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Δημιουργεί ένα νέο πλαίσιο OLE object και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο OLE object και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Δημιουργεί ένα νέο πλαίσιο OLE object και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο OLE object και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με κομμάτι CD και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Επιστρέφει τον μηδενικό-βασισμένο δείκτη της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στο καθορισμένο εύρος. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Μετακινεί τα καθορισμένα σχήματα μέσα στη συλλογή σχημάτων, τοποθετώντας τα ξεκινώντας από τον δεδομένο δείκτη. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά το αρχικοποιώντας με προεπιλεγμένη μορφοποίηση προτύπου. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Δημιουργεί ένα νέο αυτόματο ορθογώνιο σχήμα για φιλοξενία μαθηματικού περιεχομένου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας προεπιλεγμένη μορφοποίηση προτύπου. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά το αρχικοποιώντας με προεπιλεγμένο στυλ προτύπου. |
| [addGroupShape()](#addGroupShape--) | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Δημιουργεί ένα νέο σχήμα σύνδεσμου με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Δημιουργεί έναν νέο πίνακα και τον προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Δημιουργεί έναν νέο πίνακα και τον εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το σχήμα στη συγκεκριμένη θέση από τη συλλογή σχημάτων. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |
| [clear()](#clear--) | Αφαιρεί όλα τα σχήματα από τη συλλογή σχημάτων. |
| [iterator()](#iterator--) | Επιστρέφει έναν επαναλήπτη που διασχίζει τη συλλογή. |
| [iteratorJava()](#iteratorJava--) | Επιστρέφει έναν java επαναλήπτη για ολόκληρη τη συλλογή. |
| [getParentGroup()](#getParentGroup--) | Λαμβάνει το αντικείμενο γονικού σχήματος ομάδας για τη συλλογή σχημάτων. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Δημιουργεί αντίγραф του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Δημιουργεί αντίγραф του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Δημιουργεί αντίγραф του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Δημιουργεί αντίγραф του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Δημιουργεί αντίγραф του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Δημιουργεί αντίγραф του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα. |
| [isSynchronized()](#isSynchronized--) | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Επιστρέφει τη ρίζα συγχρονισμού. |
### size() {#size--}
```
public final int size()
```

Επιστρέφει τον αριθμό των στοιχείων που πραγματικά περιέχονται στη συλλογή. Μόνο για ανάγνωση int .

**Επιστρέφει:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Επιστρέφει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγματα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Δημιουργεί τη κλάση Presentation που αντιπροσωπεύει ένα αρχείο PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Πρόσβαση στην πρώτη διαφάνεια
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Προσθέτει ένα γράφημα με τα προεπιλεγμένα δεδομένα του
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Ορίζει τον τίτλο του γραφήματος
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Ορίζει την πρώτη σειρά να εμφανίζει τιμές
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Ορίζει το ευρετήριο για το φύλλο δεδομένων του γραφήματος
>      int defaultWorksheetIndex = 0;
>      // Αποκτά το φύλλο εργασίας δεδομένων του γραφήματος
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Διαγράφει τις προεπιλεγμένα παραγόμενες σειρές και κατηγορίες
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Προσθέτει νέες σειρές
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Προσθέτει νέες κατηγορίες
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Λαμβάνει την πρώτη σειρά του γραφήματος
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Συμπληρώνει τα δεδομένα της σειράς
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Ορίζει το χρώμα γεμίσματος για τη σειρά
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Λαμβάνει τη δεύτερη σειρά του γραφήματος
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Συμπληρώνει τα δεδομένα της σειράς
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Ορίζει το χρώμα γεμίσματος για τη σειρά
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Ορίζει την πρώτη ετικέτα να εμφανίζει το όνομα της Κατηγορίας
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Ορίζει τη σειρά να εμφανίζει την τιμή για την τρίτη ετικέτα
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Αποθηκεύει το αρχείο PPTX στον δίσκο
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του γραφήματος προς προσθήκη. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε points. |
| width | float | Το πλάτος του γραφήματος, σε points. |
| height | float | Το ύψος του γραφήματος, σε points. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το νεοδημιούργητο [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγματα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του γραφήματος προς προσθήκη. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε points. |
| width | float | Το πλάτος του γραφήματος, σε points. |
| height | float | Το ύψος του γραφήματος, σε points. |
| initWithSample | boolean | True για αρχικοποίηση του νέου γραφήματος με δείγματα δεδομένων σειράς και ρυθμίσεων· false για δημιουργία του γραφήματος χωρίς σειρά και μόνο με ελάχιστες ρυθμίσεις, κάτι που επιταχύνει τη δημιουργία. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το νεοδημιούργητο [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Δημιουργεί ένα SmartArt διάγραμμα και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πλαισίου του διαγράμματος, σε points. |
| y | float | Η συντεταγμένη y του πλαισίου του διαγράμματος, σε points. |
| width | float | Το πλάτος του πλαισίου του διαγράμματος, σε points. |
| height | float | Το ύψος του πλαισίου του διαγράμματος, σε points. |
| layoutType | int | Ο τύπος διάταξης SmartArt. |

**Επιστρέφει:**
[ISmartArt](../../com.aspose.slides/ismartart) - Το νεοδημιούργητο [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγματα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του γραφήματος προς δημιουργία. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε points. |
| width | float | Το πλάτος του νέου γραφήματος, σε points. |
| height | float | Το ύψος του νέου γραφήματος, σε points. |
| index | int | Ο μηδενικός-βασισμένος δείκτης στην οποία θα εισαχθεί το νέο γράφημα στη συλλογή σχημάτων. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το νεοδημιούργητο [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγματα δεδομένων σειράς και ρυθμίσεων, και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.
| x | float | Η συντεταγμένη x του νέου διαγράμματος, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου διαγράμματος, σε σημεία. |
| width | float | Το πλάτος του νέου διαγράμματος, σε σημεία. |
| height | float | Το ύψος του νέου διαγράμματος, σε σημεία. |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το νέο διάγραμμα στη συλλογή σχημάτων. |
| initWithSample | boolean | True για να αρχικοποιήσετε το νέο διάγραμμα με δεδομένα και ρυθμίσεις δείγματος σειράς· false για να δημιουργήσετε το διάγραμμα χωρίς σειρά και μόνο με ελάχιστες ρυθμίσεις, κάτι που επιταχύνει τη δημιουργία. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το νεοδημιουργημένο [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [ISlide](../../com.aspose.slides/islide) | Το [ISlide](../../com.aspose.slides/islide) που αναφέρεται από το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |

**Επιστρέφει:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νεοδημιουργημένο [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [ISlide](../../com.aspose.slides/islide) | Το [ISlide](../../com.aspose.slides/islide) που αναφέρεται από το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η εικόνα για τη διαφάνεια [IPPImage](../../com.aspose.slides/ippimage) που αναφέρεται. |

**Επιστρέφει:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νεοδημιουργημένο [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [ISlide](../../com.aspose.slides/islide) | Το [ISlide](../../com.aspose.slides/islide) που αναφέρεται από το πλαίσιο Zoom. |

**Επιστρέφει:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νεοδημιουργημένο [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Zoom με προορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Zoom στη συγκεκριμένη θέση μιας συλλογής
>  (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο διαφάνειες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [ISlide](../../com.aspose.slides/islide) | Το [ISlide](../../com.aspose.slides/islide) που αναφέρεται από το πλαίσιο Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η εικόνα για τη διαφάνεια [IPPImage](../../com.aspose.slides/ippimage) που αναφέρεται. |

**Επιστρέφει:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νεοδημιουργημένο [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Section Zoom στο τέλος μιας συλλογής
>  (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε σημεία. |
| section | [ISection](../../com.aspose.slides/isection) | Το [ISection](../../com.aspose.slides/isection) που αναφέρεται από το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

**Επιστρέφει:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νεοδημιουργημένο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom με προορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Section Zoom στο τέλος μιας συλλογής
>  (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε σημεία. |
| section | [ISection](../../com.aspose.slides/isection) | Το [ISection](../../com.aspose.slides/isection) που αναφέρεται από το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Το [IPPImage](../../com.aspose.slides/ippimage) που θα εμφανιστεί εντός του πλαισίου Section Zoom. |

**Επιστρέφει:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νεοδημιουργημένο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Section Zoom στην καθορισμένη θέση μιας συλλογής
>  (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο Section Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε σημεία. |
| section | [ISection](../../com.aspose.slides/isection) | Το [ISection](../../com.aspose.slides/isection) που αναφέρεται από το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

**Επιστρέφει:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νεοδημιουργημένο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom με προορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Section Zoom στην καθορισμένη θέση μιας συλλογής
>  (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο Section Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε σημεία. |
| section | [ISection](../../com.aspose.slides/isection) | Το [ISection](../../com.aspose.slides/isection) που αναφέρεται από το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η εικόνα που θα εμφανιστεί εντός του πλαισίου Section Zoom. |

**Επιστρέφει:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νεοδημιουργημένο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Summary Zoom στο τέλος μιας συλλογής
>  (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Summary Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Summary Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Summary Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Summary Zoom, σε σημεία. |

Αυτή η μέθοδος δημιουργεί ένα νέο Summary Zoom και τοποθετεί μια συλλογή αντικειμένων σε αυτό για όλες τις ενότητες σε αυτήν την παρουσίαση.

**Επιστρέφει:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Το νεοδημιουργημένο [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Summary Zoom στην καθορισμένη θέση μιας συλλογής
>  (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο Summary Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Summary Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Summary Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Summary Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Summary Zoom, σε σημεία. |

Αυτή η μέθοδος δημιουργεί ένα πλαίσιο Summary Zoom που συγκεντρώνει συνδέσμους σύνοψης για όλες τις ενότητες στην παρουσίαση.

**Επιστρέφει:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Το νεοδημιουργημένο [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Δημιουργεί ένα νέο πλαίσιο OLE αντικειμένου και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // Δημιουργεί τη κλάση Presentation που αντιπροσωπεύει το PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Πρόσβαση στην πρώτη διαφάνεια
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Φορτώνει ένα αρχείο cel σε ροή
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // Δημιουργεί αντικείμενο δεδομένων για ενσωμάτωση
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Προσθέτει ένα σχήμα Ole Object Frame
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Γράφει το PPTX στον δίσκο
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Οι πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Επιστρέφει:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νεοδημιουργημένο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Δημιουργεί ένα νέο πλαίσιο OLE αντικειμένου και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| className | java.lang.String | Το όνομα κλάσης του αντικειμένου OLE. |
| path | java.lang.String | Η διαδρομή του συνδεδεμένου αρχείου. |

Αυτή η διαδρομή αποθηκεύεται ακριβώς στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο θα είναι μη προσβάσιμο όταν ανοίγετε την παρουσίαση από διαφορετικό κατάλογο.

**Επιστρέφει:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νεοδημιουργημένο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Δημιουργεί ένα νέο πλαίσιο OLE αντικειμένου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει την εισαγωγή ενός αντικειμένου OLE στη δεύτερη θέση:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο OLE αντικειμένου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Οι ενσωματωμένες πληροφορίες δεδομένων OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Επιστρέφει:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νεοδημιουργημένο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το πλαίσιο αντικειμένου OLE. |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| className | java.lang.String | Το όνομα κλάσης του αντικειμένου OLE. |
| path | java.lang.String | Η διαδρομή προς το συνδεδεμένο αρχείο. |

Αυτή η διαδρομή αποθηκεύεται ακριβώς στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο θα είναι μη προσβάσιμο όταν ανοίγει η παρουσίαση από διαφορετικό φάκελο. |

**Επιστρέφει:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νεοδημιουργημένο πλαίσιο αντικειμένου OLE.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου βίντεο, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του αρχείου βίντεο προς ενσωμάτωση. |

**Επιστρέφει:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Το νεοδημιουργημένο [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου βίντεο, σε σημεία. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Το [IVideo](../../com.aspose.slides/ivideo) προς ενσωμάτωση στο πλαίσιο βίντεο. |

**Επιστρέφει:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Το νεοδημιουργημένο [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το πλαίσιο βίντεο. |
| x | float | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου βίντεο, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του αρχείου βίντεο προς ενσωμάτωση. |

**Επιστρέφει:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Το νεοδημιουργημένο [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο σε κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο σε κομμάτι CD και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο σε εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του εξωτερικού αρχείου ήχου προς σύνδεση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο σε εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του εξωτερικού αρχείου ήχου προς σύνδεση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να δημιουργήσετε ένα Audio Frame.
>  
>  // Δημιουργεί μια κλάση Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation();
>  try {
>      // Ανακτά την πρώτη διαφάνεια
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Φορτώνει το αρχείο ήχου wav σε ροή
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Προσθέτει το Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Ορίζει τη λειτουργία αναπαραγωγής και την ένταση του ήχου
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Γράφει το αρχείο PowerPoint στον δίσκο
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio_stream | java.io.InputStream | Ένα ρεύμα εισόδου που περιέχει δεδομένα ήχου WAV προς ενσωμάτωση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio_stream | java.io.InputStream | Ένα ρεύμα εισόδου που περιέχει δεδομένα ήχου WAV προς ενσωμάτωση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Μια [IAudio](../../com.aspose.slides/iaudio) από τη συλλογή Presentation.Audios. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Μια [IAudio](../../com.aspose.slides/iaudio) από τη συλλογή Presentation.Audios προς ενσωμάτωση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Επιστρέφει τον μηδενικό δείκτη της πρώτης εμφάνισης του συγκεκριμένου σχήματος στη συλλογή.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Το σχήμα που πρέπει να εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Ο μηδενικός δείκτης της πρώτης εμφάνισης του σχήματος στη συλλογή σχημάτων, εάν βρεθεί· διαφορετικά, \\u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα.

**Επιστρέφει:**
com.aspose.slides.IShape[] - Ένας πίνακας αντικειμένων [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στο καθορισμένο εύρος.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Ο δείκτης του πρώτου σχήματος που θα επιστραφεί. |
| count | int | Ο αριθμός των σχημάτων που θα επιστραφούν. |

**Επιστρέφει:**
com.aspose.slides.IShape[] - Ένας πίνακας αντικειμένων [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Μετακινεί το συγκεκριμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στόχου όπου θα τοποθετηθεί το σχήμα. |
| shape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) που θα μετακινηθεί στη συλλογή. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Μετακινεί τα συγκεκριμένα σχήματα μέσα στη συλλογή σχημάτων, τοποθετώντας τα ξεκινώντας από τον δοθέντα δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στόχου όπου θα τοποθετηθεί το πρώτο σχήμα· τα επόμενα σχήματα ακολουθούν στη σειρά που παρέχεται. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Ένα ή περισσότερα [IShape](../../com.aspose.slides/ishape) στιγμιότυπα για μετακίνηση στη συλλογή. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος προς προσθήκη. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά αρχικοποιώντας το με προεπιλεγμένη μορφοποίηση προτύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος προς προσθήκη. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |
| createFromTemplate | boolean | True για εφαρμογή προεπιλεγμένου στυλ προτύπου (απλό στυλ, κεντραρισμένο κείμενο και μη κενό όνομα) στο νέο σχήμα· false για δημιουργία του σχήματος με όλες τις ιδιότητες στις προεπιλεγμένες τιμές. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Δημιουργεί ένα νέο αυτόματο ορθογώνιο σχήμα για φιλοξενία μαθηματικού περιεχομένου και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε μια μαθηματική εξίσωση σε παρουσίαση PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας προεπιλεγμένη μορφοποίηση προτύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το νέο αυτόματο σχήμα. |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος προς εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά αρχικοποιώντας το με προεπιλεγμένο στυλ προτύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το αυτόματο σχήμα. |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος προς εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |
| createFromTemplate | boolean | True για εφαρμογή προεπιλεγμένου στυλ προτύπου (συμπεριλαμβανομένου μη κενών ονόματος, απλού στυλ και κεντραρισμένου κειμένου)· false για δημιουργία του σχήματος με όλες τις ιδιότητες στις προεπιλεγμένες τιμές. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να χωρά όλα τα σχήματα που προστίθενται σε αυτήν.

--------------------

> ```
> Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα group shape σε μια διαφάνεια παρουσίασης PowerPoint.
>  
>  // Δημιουργεί κλάση Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Λαμβάνει την πρώτη διαφάνεια
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Πρόσβαση στη συλλογή σχημάτων των διαφανειών
>      IShapeCollection slideShapes = sld.getShapes();
>      // Προσθήκη group shape στη διαφάνεια
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Προσθήκη σχημάτων μέσα στο προστεθέν group shape
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Προσθήκη πλαισίου group shape
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Γράψιμο του αρχείου PPTX στον δίσκο
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Το νεοδημιουργημένο [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη SVG-εικόνα σε μεμονωμένα σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Το [ISvgImage](../../com.aspose.slides/isvgimage) που περιέχει διανυσματικό περιεχόμενο προς μετατροπή σε σχήματα. |
| x | float | Η συντεταγμένη x του πλαισίου της ομάδας, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου της ομάδας, σε πόντους. |
| width | float | Το πλάτος του πλαισίου της ομάδας, σε πόντους. |
| height | float | Το ύψος του πλαισίου της ομάδας, σε πόντους. |

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Το νεοδημιουργημένο [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Δημιουργεί ένα νέο κενό σχήμα ομάδας και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να χωρά όλα τα σχήματα που προστίθενται σε αυτήν.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το σχήμα ομάδας. |

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Το νεοδημιουργημένο [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο σχήμα σύνδεσης με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Το ακόλουθο παράδειγμα δείχνει πώς να προσθέσετε έναν σύνδεσμο (καμπυλωτό σύνδεσμο) μεταξύ δύο σχημάτων (έλλειψης και ορθογωνίου) σε παρουσίαση PowerPoint.
>  
>  // Δημιουργεί μια κλάση παρουσίασης που αντιπροσωπεύει ένα αρχείο PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Προσπελαύνει τη συλλογή σχημάτων για μια συγκεκριμένη διαφάνεια
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Προσθέτει ένα αυτόματο σχήμα έλλειψης
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Προσθέτει ένα αυτόματο σχήμα ορθογωνίου
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Προσθέτει ένα σχήμα σύνδεσμου στη συλλογή σχημάτων της διαφάνειας
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Συνδέει τα σχήματα χρησιμοποιώντας το σύνδεσμο
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Καλεί τη μέθοδο reroute που ορίζει τη σύντομη αυτόματη διαδρομή μεταξύ των σχημάτων
>      connector.reroute();
>      // Αποθηκεύει την παρουσίαση
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσης προς προσθήκη. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |

**Επιστρέφει:**
[IConnector](../../com.aspose.slides/iconnector) - Το νεοδημιουργημένο [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο σχήμα σύνδεσης και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσης για δημιουργία. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |
| createFromTemplate | boolean | True για εφαρμογή προεπιλεγμένου στυλ προτύπου (μη κενό όνομα, απλό στυλ)· false για δημιουργία του σύνδεσμου με προεπιλεγμένες τιμές ιδιοτήτων. |

**Επιστρέφει:**
[IConnector](../../com.aspose.slides/iconnector) - Το νεοδημιουργημένο [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας προεπιλεγμένο στυλ προτύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το σχήμα σύνδεσης. |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσης για εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |

**Επιστρέφει:**
[IConnector](../../com.aspose.slides/iconnector) - Το νεοδημιουργημένο [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το σχήμα σύνδεσης. |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσης για εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |
| createFromTemplate | boolean | True για εφαρμογή προεπιλεγμένου στυλ προτύπου (μη κενό όνομα, απλό στυλ)· false για δημιουργία του σύνδεσμου με προεπιλεγμένες τιμές ιδιοτήτων. |

**Επιστρέφει:**
[IConnector](../../com.aspose.slides/iconnector) - Το νεοδημιουργημένο [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Καθορίζει τον τύπο σχήματος που περιέχει το [ShapeType](../../com.aspose.slides/shapetype), εκτός από όλους τους τύπους γραμμών: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Η συντεταγμένη x του πλαισίου εικόνας, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου εικόνας, σε πόντους. |
| width | float | Το πλάτος του πλαισίου εικόνας, σε πόντους. |
| height | float | Το ύψος του πλαισίου εικόνας, σε πόντους. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Το [IPPImage](../../com.aspose.slides/ippimage) που θα εμφανιστεί στο πλαίσιο εικόνας. |

**Επιστρέφει:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Το νεοδημιουργημένο [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στη θέση που θα εισαχθεί το πλαίσιο εικόνας. |
| shapeType | int | Καθορίζει τον τύπο σχήματος που περιέχει το [ShapeType](../../com.aspose.slides/shapetype), εκτός από όλους τους τύπους γραμμών: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Η συντεταγμένη x του πλαισίου εικόνας, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου εικόνας, σε πόντους. |
| width | float | Το πλάτος του πλαισίου εικόνας, σε πόντους. |
| height | float | Το ύψος του πλαισίου εικόνας, σε πόντους. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Το [IPPImage](../../com.aspose.slides/ippimage) που θα εμφανιστεί στο πλαίσιο εικόνας. |

**Επιστρέφει:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Το νεοδημιουργημένο [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Δημιουργεί έναν νέο πίνακα και τον προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Τα παρακάτω παραδείγματα δείχνουν πώς να προσθέσετε πίνακα σε παρουσίαση PowerPoint.
>  
>  // Δημιουργεί κλάση Presentation που αντιπροσωπεύει αρχείο PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Πρόσβαση στην πρώτη διαφάνεια
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Ορίζει στήλες με πλάτη και γραμμές με ύψη
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Προσθήκη σχήματος πίνακα στη διαφάνεια
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Ορισμός μορφοποίησης περιγράμματος για κάθε κελί
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // Συγχώνευση κελιών 1 & 2 της γραμμής 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Προσθήκη κειμένου στο συγχωνευμένο κελί
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Αποθήκευση του PPTX στον δίσκο
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του πίνακα, σε πόντους. |
| y | float | Η y-συντεταγμένη του πίνακα, σε πόντους. |
| columnWidths | double[] | Ένας πίνακας διπλών αριθμών που αντιπροσωπεύει το πλάτος των στηλών του πίνακα, σε πόντους. |
| rowHeights | double[] | Ένας πίνακας διπλών αριθμών που αντιπροσωπεύει το ύψος των γραμμών του πίνακα, σε πόντους. |

**Επιστρέφει:**
[ITable](../../com.aspose.slides/itable) - Το πρόσφατα δημιουργημένο [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Δημιουργεί έναν νέο πίνακα και τον εισάγει στη συλλογή σ shape στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης βάσει μηδέν όπου θα εισαχθεί ο πίνακας. |
| x | float | Η x-συντεταγμένη του πίνακα, σε πόντους. |
| y | float | Η y-συντεταγμένη του πίνακα, σε πόντους. |
| columnWidths | double[] | Ένας πίνακας διπλών αριθμών που αντιπροσωπεύει το πλάτος των στηλών του πίνακα, σε πόντους. |
| rowHeights | double[] | Ένας πίνακας διπλών αριθμών που αντιπροσωπεύει το ύψος των γραμμών του πίνακα, σε πόντους. |

**Επιστρέφει:**
[ITable](../../com.aspose.slides/itable) - Το πρόσφατα δημιουργημένο [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Αφαιρεί το σχήμα στον καθορισμένο δείκτη από τη συλλογή σ shape.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης βάσει μηδέν του σχήματος που θα αφαιρεθεί. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σ shape.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) προς αφαίρεση. |

### clear() {#clear--}
```
public final void clear()
```

Αφαιρεί όλα τα σχήματα από τη συλλογή σ shape.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Επιστρέφει έναν αριθμητή που διατρέχει τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Ένας IGenericEnumerator που μπορεί να χρησιμοποιηθεί για την διαπέραση της συλλογής.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή.

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Ένας java.util.Iterator για ολόκληρη τη συλλογή.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Αποκτά το αντικείμενο σχήματος γονικής ομάδας για τη συλλογή shape. Μόνο για ανάγνωση [IGroupShape](../../com.aspose.slides/igroupshape).

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σ shape.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το σχήμα για αντιγραφή. |
| x | float | Η x-συντεταγμένη του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του νέου σχήματος, σε πόντους. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σ shape. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το σχήμα για αντιγραφή. |
| x | float | Η x-συντεταγμένη του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του νέου σχήματος, σε πόντους. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σ shape. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) για κλωνοποίηση. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σ shape στον καθορισμένο δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης βάσει μηδέν όπου θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) για κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σ shape στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης βάσει μηδέν όπου θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) για κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σ shape στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης βάσει μηδέν όπου θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) για κλωνοποίηση. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Αντιγράφει όλα τα στοιχεία από τη συλλογή στον καθορισμένο πίνακα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Πίνακας προορισμού. |
| index | int | Αρχικός δείκτης στον πίνακα προορισμού. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο για ανάγνωση  boolean .

**Επιστρέφει:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Επιστρέφει μια ρίζα συγχρονισμού. Μόνο για ανάγνωση  Object .

**Επιστρέφει:**
java.lang.Object