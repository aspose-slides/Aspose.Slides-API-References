---
title: IShapeCollection
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει μια συλλογή σχημάτων.
type: docs
url: /el/com.aspose.slides/ishapecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Αντιπροσωπεύει μια συλλογή σχημάτων.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στο καθορισμένο δείκτη. |
| [getParentGroup()](#getParentGroup--) | Λαμβάνει το αντικείμενο γονικής ομάδας σχήματος για τη συλλογή σχημάτων. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Επιστρέφει τον μηδενικής βάσης δείκτη της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στο καθορισμένο εύρος. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Μετακινεί τα καθορισμένα σχήματα στη συλλογή σχημάτων, τοποθετώντας τα αρχίζοντας από τον δεδομένο δείκτη. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά το αρχικοποιώντας με προεπιλεγμένη μορφοποίηση προτύπου. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Δημιουργεί ένα νέο ορθογώνιο αυτόματο σχήμα για φιλοξενία μαθηματικού περιεχομένου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, εφαρμόζοντας προεπιλεγμένη μορφοποίηση προτύπου. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, προαιρετικά το αρχικοποιώντας με προεπιλεγμένο στυλ προτύπου. |
| [addGroupShape()](#addGroupShape--) | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Δημιουργεί ένα νέο σχήμα σύνδεσμου με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Δημιουργεί έναν νέο πίνακα και τον προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Δημιουργεί έναν νέο πίνακα και τον εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το σχήμα στον καθορισμένο δείκτη από τη συλλογή σχημάτων. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |
| [clear()](#clear--) | Αφαιρεί όλα τα σχήματα από τη συλλογή σχημάτων. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο ανάγνωση [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Λαμβάνει το αντικείμενο γονικής ομάδας σχήματος για τη συλλογή σχημάτων. Μόνο ανάγνωση [IGroupShape](../../com.aspose.slides/igroupshape).

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Ο τύπος του γραφήματος που θα προστεθεί. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε σημεία. |
| width | float | Το πλάτος του γραφήματος, σε σημεία. |
| height | float | Το ύψος του γραφήματος, σε σημεία. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Το νεοδημιούργητο [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Ο τύπος του γραφήματος που θα προστεθεί. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε σημεία. |
| width | float | Το πλάτος του γραφήματος, σε σημεία. |
| height | float | Το ύψος του γραφήματος, σε σημεία. |
| initWithSample | boolean | Αληθές για αρχικοποίηση του νέου γραφήματος με δείγμα δεδομένων σειράς και ρυθμίσεων· ψευδές για δημιουργία γραφήματος χωρίς σειρές και μόνο με ελάχιστες ρυθμίσεις, ώστε η δημιουργία να είναι γρηγορότερη. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Το νεοδημιούργητο [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πλαισίου του διαγράμματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του διαγράμματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του διαγράμματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του διαγράμματος, σε σημεία. |
| layoutType | int | Ο τύπος διάταξης SmartArt. |

**Returns:**
[ISmartArt](../../com.aspose.slides/ismartart) - Το νεοδημιούργητο [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Ο τύπος του γραφήματος που θα δημιουργηθεί. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε σημεία. |
| width | float | Το πλάτος του νέου γραφήματος, σε σημεία. |
| height | float | Το ύψος του νέου γραφήματος, σε σημεία. |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το νέο γράφημα στη συλλογή σχημάτων. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Το νεοδημιούργητο [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Ο τύπος του γραφήματος που θα δημιουργηθεί. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε σημεία. |
| width | float | Το πλάτος του νέου γραφήματος, σε σημεία. |
| height | float | Το ύψος του νέου γραφήματος, σε σημεία. |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το νέο γράφημα στη συλλογή σχημάτων. |
| initWithSample | boolean | Αληθές για αρχικοποίηση του νέου γραφήματος με δείγμα δεδομένων σειράς και ρυθμίσεων· ψευδές για δημιουργία γραφήματος χωρίς σειρές και μόνο με ελάχιστες ρυθμίσεις, ώστε η δημιουργία να είναι γρηγορότερη. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Το νεοδημιούργητο [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Οι ενσωματωμένες πληροφορίες δεδομένων OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νεοδημιούργητο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| className | java.lang.String | Το όνομα κλάσης του αντικειμένου OLE. |
| path | java.lang.String | Η διαδρομή προς το συνδεδεμένο αρχείο.

Αυτή η διαδρομή αποθηκεύεται ακριβώς όπως είναι στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο δεν θα είναι προσβάσιμο όταν ανοίξετε την παρουσίαση από διαφορετικό φάκελο. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νεοδημιούργητο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο αντικειμένου OLE. |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Οι ενσωματωμένες πληροφορίες δεδομένων OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νεοδημιούργητο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο αντικειμένου OLE. |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| className | java.lang.String | Το όνομα κλάσης του αντικειμένου OLE. |
| path | java.lang.String | Η διαδρομή προς το συνδεδεμένο αρχείο.

Αυτή η διαδρομή αποθηκεύεται ακριβώς όπως είναι στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο δεν θα είναι προσβάσιμο όταν ανοίξετε την παρουσίαση από διαφορετικό φάκελο. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νεοδημιούργητο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [ISlide](../../com.aspose.slides/islide) | Η [ISlide](../../com.aspose.slides/islide) στην οποία αναφέρεται το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νεοδημιούργητο [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Zoom στο τέλος μιας συλλογής
>  (υποθέστε ότι υπάρχουν τουλάχιστον δύο διαφάνειες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [ISlide](../../com.aspose.slides/islide) | Η [ISlide](../../com.aspose.slides/islide) στην οποία αναφέρεται το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η εικόνα για τη διαφανή [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νεοδημιούργητο [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [ISlide](../../com.aspose.slides/islide) | Η [ISlide](../../com.aspose.slides/islide) στην οποία αναφέρεται το πλαίσιο Zoom. |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νεοδημιούργητο [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Zoom στον καθορισμένο δείκτη μιας συλλογής
>  (υποθέστε ότι υπάρχουν τουλάχιστον δύο διαφάνειες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [ISlide](../../com.aspose.slides/islide) | Η [ISlide](../../com.aspose.slides/islide) στην οποία αναφέρεται το πλαίσιο Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η εικόνα για τη διαφανή [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νεοδημιούργητο [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Section Zoom στο τέλος μιας συλλογής
>  (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου Section Zoom, σε σημεία. |
| section | [ISection](../../com.aspose.slides/isection) | Η [ISection](../../com.aspose.slides/isection) στην οποία αναφέρεται το Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νεοδημιούργητο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Section Zoom στο τέλος μιας συλλογής
>  (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου Section Zoom, σε σημεία. |
| section | [ISection](../../com.aspose.slides/isection) | Η [ISection](../../com.aspose.slides/isection) στην οποία αναφέρεται το Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η [IPPImage](../../com.aspose.slides/ippimage) που θα εμφανιστεί εντός του Section Zoom. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νεοδημιούργητο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Section Zoom στο καθορισμένο δείκτη μιας συλλογής
>  (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το Section Zoom. |
| x | float | Η συντεταγμένη x του νέου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου Section Zoom, σε σημεία. |
| section | [ISection](../../com.aspose.slides/isection) | Η [ISection](../../com.aspose.slides/isection) στην οποία αναφέρεται το Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νεοδημιούργητο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Section Zoom στον καθορισμένο δείκτη μιας συλλογής
>  (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το Section Zoom. |
| x | float | Η συντεταγμένη x του νέου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου Section Zoom, σε σημεία. |
| section | [ISection](../../com.aspose.slides/isection) | Η [ISection](../../com.aspose.slides/isection) στην οποία αναφέρεται το Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η εικόνα που θα εμφανιστεί εντός του Section Zoom. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νεοδημιούργητο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Summary Zoom στο τέλος μιας συλλογής
>  (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου Summary Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου Summary Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου Summary Zoom, σε σημεία. |
| height | float | Το ύψος του νέου Summary Zoom, σε σημεία. |

Αυτή η μέθοδος δημιουργεί ένα Summary Zoom που συγκεντρώνει συνδέσμους σύνοψης για όλες τις ενότητες στην παρουσίαση.

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Το νεοδημιούργητο [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Summary Zoom στον καθορισμένο δείκτη μιας συλλογής
>  (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το Summary Zoom. |
| x | float | Η συντεταγμένη x του νέου Summary Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου Summary Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου Summary Zoom, σε σημεία. |
| height | float | Το ύψος του νέου Summary Zoom, σε σημεία. |

Αυτή η μέθοδος δημιουργεί ένα Summary Zoom που συγκεντρώνει συνδέσμους σύνοψης για όλες τις ενότητες στην παρουσίαση.

**Returns:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Το νεοδημιούργητο [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου βίντεο, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του αρχείου βίντεο που θα ενσωματωθεί. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Το νεοδημιούργητο [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου βίντεο, σε σημεία. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Η [IVideo](../../com.aspose.slides/ivideo) που θα ενσωματωθεί στο πλαίσιο βίντεο. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Το νεοδημιούργητο [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο βίντεο. |
| x | float | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | float | Το ύψος του νέου πλα

ίου βίντεο, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του αρχείου βίντεο που θα ενσωματωθεί. |

**Returns:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Το νεοδημιούργητο [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιούργητο [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιούργητο [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του εξωτερικού αρχείου ήχου που θα συνδεθεί. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιούργητο [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του εξωτερικού αρχείου ήχου που θα συνδεθεί. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιούργητο [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. Το ενσωματωμένο ήχο προστίθεται στη συλλογή Presentation.Audios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio_stream | java.io.InputStream | Ένα ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιούργητο [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Μια [IAudio](../../com.aspose.slides/iaudio) από τη συλλογή Presentation.Audios. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιούργητο [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το ενσωματωμένο ήχο προστίθεται στη συλλογή Presentation.Audios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio_stream | java.io.InputStream | Ένα ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιούργητο [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Μια [IAudio](../../com.aspose.slides/iaudio) από τη συλλογή Presentation.Audios για ενσωμάτωση. |

**Returns:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιούργητο [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Επιστρέφει τον μηδενικής βάσης δείκτη της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Το σχήμα που θα εντοπιστεί στη συλλογή. |

**Returns:**
int - Ο μηδενικής βάσης δείκτης της πρώτης εμφάνισης του σχήματος στη συλλογή σχημάτων εάν βρεθεί· διαφορετικά, \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα.

**Returns:**
com.aspose.slides.IShape[] - Ένας πίνακας αντικειμένων [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στο καθορισμένο εύρος.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Η θέση του πρώτου σχήματος που θα επιστραφεί. |
| count | int | Ο αριθμός των σχημάτων που θα επιστραφούν. |

**Returns:**
com.aspose.slides.IShape[] - Ένας πίνακας αντικειμένων [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης προορισμού όπου θα τοποθετηθεί το σ形μα. |
| shape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) που θα μετακινηθεί στη συλλογή. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Μετακινεί τα καθορισμένα σχήματα στη συλλογή σχημάτων, αρχίζοντας από τον δεδομένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης προορισμού όπου θα τοποθετηθεί το πρώτο καθορισμένο σχήμα· τα επακόλουθα σχήματα ακολουθούν με τη σειρά που δόθηκαν. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Μία ή περισσότερες [IShape](../../com.aspose.slides/ishape) που θα μετακινηθούν στη συλλογή. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος που θα προστεθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιούργητο [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά το αρχικοποιώντας με προεπιλεγμένη μορφοποίηση προτύπου.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος που θα προστεθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |
| createFromTemplate | boolean | Αληθές για εφαρμογή προεπιλεγμένου στυλ προτύπου (απλό στυλ, κεντραρισμένο κείμενο, μη κενό όνομα) στο νέο σχήμα· ψευδές για δημιουργία σχήματος με όλες τις ιδιότητες στις προεπιλεγμένες τιμές τους. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιούργητο [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Δημιουργεί ένα νέο ορθογώνιο αυτόματο σχήμα για φιλοξενία μαθηματικού περιεχομένου και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιούργητο [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, εφαρμόζοντας προεπιλεγμένη μορφοποίηση προτύπου.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το νέο αυτόματο σχήμα. |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος που θα εισαχθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιούργητο [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, προαιρετικά το αρχικοποιώντας με προεπιλεγμένο στυλ προτύπου.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το αυτόματο σχήμα. |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος που θα εισαχθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |
| createFromTemplate | boolean | Αληθές για εφαρμογή προεπιλεγμένου στυλ προτύπου (συμπεριλαμβανομένου μη κενό όνομα, απλό στυλ, κεντραρισμένο κείμενο)· ψευδές για δημιουργία σχήματος με όλες τις ιδιότητες στις προεπιλεγμένες τιμές τους. |

**Returns:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νεοδημιούργητο [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να φιλοξενεί οποιαδήποτε σχήματα προστεθούν σε αυτήν.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Το νεοδημιούργητο [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Το [ISvgImage](../../com.aspose.slides/isvgimage) που περιέχει διανυσματικό περιεχόμενο προς μετατροπή σε σχήματα. |
| x | float | Η συντεταγμένη x του πλαισίου της ομάδας, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου της ομάδας, σε σημεία. |
| width | float | Το πλάτος του πλαισίου της ομάδας, σε σημεία. |
| height | float | Το ύψος του πλαισίου της ομάδας, σε σημεία. |

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Το νεοδημιούργητο [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Δημιουργεί ένα νέο κενό σχήμα ομάδας και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να φιλοξενεί οποιαδήποτε σχήματα προστεθούν σε αυτήν.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το σχήμα ομάδας. |

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Το νεοδημιούργητο [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο σχήμα σύνδεσμου με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσμου που θα προστεθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε σημεία. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - Το νεοδημιούργητο [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο σχήμα σύνδεσμου και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσμου που θα δημιουργηθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε σημεία. |
| createFromTemplate | boolean | Αληθές για εφαρμογή προεπιλεγμένου στυλ προτύπου (μη κενό όνομα, απλό στυλ)· ψευδές για δημιουργία σύνδεσμου με προεπιλεγμένες τιμές ιδιοτήτων. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - Το νεοδημιούργητο [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, εφαρμόζοντας προεπιλεγμένο στυλ προτύπου.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το σχήμα σύνδεσμου. |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσμου που θα εισαχθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε σημεία. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - Το νεοδημιούργητο [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το σχήμα σύνδεσμου. |
| shapeType | int | Ο [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσμου που θα εισαχθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε σημεία. |
| createFromTemplate | boolean | Αληθές για εφαρμογή προεπιλεγμένου στυλ προτύπου (μη κενό όνομα, απλό στυλ)· ψευδές για δημιουργία σύνδεσμου με προεπιλεγμένες τιμές ιδιοτήτων. |

**Returns:**
[IConnector](../../com.aspose.slides/iconnector) - Το νεοδημιούργητο [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Καθορίζει τον τύπο σχήματος που περιέχεται στο [ShapeType](../../com.aspose.slides/shapetype), εκτός από όλους τους τύπους γραμμών:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | Η συντεταγμένη x του πλαισίου εικόνας, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου εικόνας, σε σημεία. |
| width | float | Το πλάτος του πλαισίου εικόνας, σε σημεία. |
| height | float | Το ύψος του πλαισίου εικόνας, σε σημεία. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η [IPPImage](../../com.aspose.slides/ippimage) που θα εμφανιστεί στο πλαίσιο εικόνας. |

**Returns:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Το νεοδημιούργητο [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το πλαίσιο εικόνας. |
| shapeType | int | Καθορίζει τον τύπο σχήματος που περιέχεται στο [ShapeType](../../com.aspose.slides/shapetype), εκτός από όλους τους τύπους γραμμών:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | Η συντεταγμένη x του πλαισίου εικόνας, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου εικόνας, σε σημεία. |
| width | float | Το πλάτος του πλαισίου εικόνας, σε σημεία. |
| height | float | Το ύψος του πλαισίου εικόνας, σε σημεία. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η [IPPImage](../../com.aspose.slides/ippimage) που θα εμφανιστεί στο πλαίσιο εικόνας. |

**Returns:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Το νεοδημιούργητο [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Δημιουργεί έναν νέο πίνακα και τον προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πίνακα, σε σημεία. |
| y | float | Η συντεταγμένη y του πίνακα, σε σημεία. |
| columnWidths | double[] | Πίνακας διπλών που αντιπροσωπεύει το πλάτος των στηλών του πίνακα, σε σημεία. |
| rowHeights | double[] | Πίνακας διπλών που αντιπροσωπεύει το ύψος των γραμμών του πίνακα, σε σημεία. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - Το νεοδημιούργητο [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Δημιουργεί έναν νέο πίνακα και τον εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί ο πίνακας. |
| x | float | Η συντεταγμένη x του πίνακα, σε σημεία. |
| y | float | Η συντεταγμένη y του πίνακα, σε σημεία. |
| columnWidths | double[] | Πίνακας διπλών που αντιπροσωπεύει το πλάτος των στηλών του πίνακα, σε σημεία. |
| rowHeights | double[] | Πίνακας διπλών που αντιπροσωπεύει το ύψος των γραμμών του πίνακα, σε σημεία. |

**Returns:**
[ITable](../../com.aspose.slides/itable) - Το νεοδημιούργητο [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το σχήμα στον καθορισμένο δείκτη από τη συλλογή σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης του σχήματος που θα αφαιρεθεί. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) που θα αφαιρεθεί. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλα τα σχήματα από τη συλλογή σχημάτων.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το σχήμα που θα κλωνοποιηθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Το νεοδημιούργητο [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του  sourceShape .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) που θα κλωνοποιηθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Το νεοδημιούργητο [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλωνοποιημένο σχήμα διατηρεί την αρχική θέση και μέγεθος.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) που θα κλωνοποιηθεί. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Το νεοδημιούργητο [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) που θα κλωνοποιηθεί. |
| x | float | Η συντεταγμένη x του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του κλωνοποιημένου σχήματος, σε σημεία. |
| width | float | Το πλάτος του κλωνοποιημένου σχήματος, σε σημεία. |
| height | float | Το ύψος του κλωνοποιημένου σχήματος, σε σημεία. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Το νεοδημιούργητο [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του  sourceShape .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) που θα κλωνοποιηθεί. |
| x | float | Η συντεταγμένη x του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του κλωνοποιημένου σχήματος, σε σημεία. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Το νεοδημιούργητο [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί την αρχική θέση και μέγεθος.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης όπου θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) που θα κλωνοποιηθεί. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - Το νεοδημιούργητο [IShape](../../com.aspose.slides/ishape).