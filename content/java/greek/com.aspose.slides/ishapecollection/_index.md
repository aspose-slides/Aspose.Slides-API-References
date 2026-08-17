---
title: IShapeCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει μια συλλογή σχημάτων.
type: docs
url: /el/com.aspose.slides/ishapecollection/
---
**Όλες οι Υλοποιημένες Διασυνδέσεις:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Αντιπροσωπεύει μια συλλογή σχημάτων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Αποκτά το στοιχείο στην καθορισμένη θέση. |
| [getParentGroup()](#getParentGroup--) | Αποκτά το αντικείμενο γονικού ομαδικού σχήματος για τη συλλογή σχημάτων. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Δημιουργεί ένα διάγραμμα SmartArt και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Zoom με προκαθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προκαθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προκαθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με κομμάτι CD και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Επιστρέφει το μηδενικό ευρετήριο της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |
| [toArray()](#toArray--) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στο καθορισμένο εύρος. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Μετακινεί τα καθορισμένα σχήματα στη συλλογή σχημάτων, τοποθετώντας τα ξεκινώντας από το δεδομένο ευρετήριο. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά αρχικοποιώντας το με προεπιλεγμένη μορφοποίηση προτύπου. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Δημιουργεί ένα νέο αυτόματο σχήμα ορθογωνίου για τη φιλοξενία μαθηματικού περιεχομένου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση, εφαρμόζοντας προεπιλεγμένη μορφοποίηση προτύπου. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση, προαιρετικά αρχικοποιώντας το με προεπιλεγμένο στυλ προτύπου. |
| [addGroupShape()](#addGroupShape--) | Δημιουργεί ένα νέο κενό ομαδικό σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Δημιουργεί ένα νέο ομαδικό σχήμα, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σχήματα και προσθέτει το προκύπτον ομαδικό σχήμα στο τέλος της συλλογής σχημάτων. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Δημιουργεί ένα νέο κενό ομαδικό σχήμα και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Δημιουργεί ένα νέο σχήμα σύνδεσης με προεπιλεγμένο στυλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση, εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση, προαιρετικά εφαρμόζοντας προεπιλεγμένο στυλ προτύπου. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Δημιουργεί ένα νέο πίνακα και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Δημιουργεί ένα νέο πίνακα και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το σχήμα στη καθορισμένη θέση από τη συλλογή σχημάτων. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Αφαιρέτει την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |
| [clear()](#clear--) | Αφαιρεί όλα τα σχήματα από τη συλλογή σχημάτων. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Αποκτά το στοιχείο στη καθορισμένη θέση. Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Αποκτά το αντικείμενο γονικού ομαδικού σχήματος για τη συλλογή σχημάτων. Μόνο για ανάγνωση [IGroupShape](../../com.aspose.slides/igroupshape).

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του γράφηματος προς προσθήκη. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε points. |
| width | float | Το πλάτος του γραφήματος, σε points. |
| height | float | Το ύψος του γραφήματος, σε points. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το νέο δημιουργημένο [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του γράφηματος προς προσθήκη. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε points. |
| width | float | Το πλάτος του γραφήματος, σε points. |
| height | float | Το ύψος του γραφήματος, σε points. |
| initWithSample | boolean | True για την αρχικοποίηση του νέου γραφήματος με δείγμα δεδομένων σειράς και ρυθμίσεις· false για τη δημιουργία του γραφήματος χωρίς σειρά και μόνο ελάχιστες ρυθμίσεις, κάτι που κάνει τη δημιουργία πιο γρήγορη. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το νέο δημιουργημένο [IChart](../../com.aspose.slides/ichart).

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


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πλαισίου του διαγράμματος, σε points. |
| y | float | Η συντεταγμένη y του πλαισίου του διαγράμματος, σε points. |
| width | float | Το πλάτος του πλαισίου του διαγράμματος, σε points. |
| height | float | Το ύψος του πλαισίου του διαγράμματος, σε points. |
| layoutType | int | Ο τύπος διάταξης SmartArt. |

**Επιστρέφει:**
[ISmartArt](../../com.aspose.slides/ismartart) - Το νέο δημιουργημένο [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του γράφηματος προς δημιουργία. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε points. |
| width | float | Το πλάτος του νέου γραφήματος, σε points. |
| height | float | Το ύψος του νέου γραφήματος, σε points. |
| index | int | Το μηδενικό ευρετήριο στη θέση που θα εισαχθεί το νέο γράφημα στη συλλογή σχημάτων. |

**Επιστρέφει:**
[IChart](../../com.aspose.slides/ichart) - Το νέο δημιουργημένο [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Δημιουργεί ένα νέο γράφημα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεις, και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του γράφηματος προς δημιουργία. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε points. |
| width | float | Το πλάτος του νέου γραφήματος, σε points. |
| height | float | Το ύψος του νέου γραφήματος, σε points. |
| index | int | Το μηδενικό ευρετήριο στη θέση που θα εισαχθεί το νέο γράφημα στη συλλογή σχημάτων. |
| initWithSample | boolean | True για αρχικοποίηση του νέου chart με δεδομένα και ρυθμίσεις δείγματος σειράς· false για δημιουργία του chart χωρίς σειρά και μόνο ελάχιστες ρυθμίσεις, κάτι που κάνει τη δημιουργία πιο γρήγορη. |

**Επιστρέφει:**  
[IChart](../../com.aspose.slides/ichart) - Το νέο δημιουργημένο [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε points. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε points. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Οι πληροφορίες ενσωματωμένων δεδομένων OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Επιστρέφει:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νέο δημιουργημένο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε points. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε points. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε points. |
| className | java.lang.String | Το όνομα κλάσης του αντικειμένου OLE. |
| path | java.lang.String | Η διαδρομή προς το συνδεδεμένο αρχείο.  

Αυτή η διαδρομή αποθηκεύεται ακριβώς όπως εισήχθη στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο δεν θα είναι προσβάσιμο όταν ανοίγει η παρουσίαση από διαφορετικό κατάλογο. |

**Επιστρέφει:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νέο δημιουργημένο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το πλαίσιο αντικειμένου OLE. |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε points. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε points. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε points. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Οι πληροφορίες ενσωματωμένων δεδομένων OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Επιστρέφει:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νέο δημιουργημένο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το πλαίσιο αντικειμένου OLE. |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε points. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε points. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε points. |
| className | java.lang.String | Το όνομα κλάσης του αντικειμένου OLE. |
| path | java.lang.String | Η διαδρομή προς το συνδεδεμένο αρχείο.  

Αυτή η διαδρομή αποθηκεύεται ακριβώς όπως εισήχθη στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο δεν θα είναι προσβάσιμο όταν ανοίγει η παρουσίαση από διαφορετικό κατάλογο. |

**Επιστρέφει:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Το νέο δημιουργημένο [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

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


**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε points. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε points. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Το [ISlide](../../com.aspose.slides/islide) στο οποίο αναφέρεται το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |

**Επιστρέφει:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νέο δημιουργημένο [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
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
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε points. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε points. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Το [ISlide](../../com.aspose.slides/islide) στο οποίο αναφέρεται το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η εικόνα για τη διαφάνεια [IPPImage](../../com.aspose.slides/ippimage) στην οποία αναφέρεται. |

**Επιστρέφει:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νέο δημιουργημένο [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

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
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το πλαίσιο Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε points. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε points. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Το [ISlide](../../com.aspose.slides/islide) στο οποίο αναφέρεται το πλαίσιο Zoom. |

**Επιστρέφει:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νέο δημιουργημένο [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Zoom με προκαθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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


**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το πλαίσιο Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε points. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε points. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε points. |
| slide | [ISlide](../../com.aspose.slides/islide) | Το [ISlide](../../com.aspose.slides/islide) στο οποίο αναφέρεται το πλαίσιο Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η εικόνα για τη διαφάνεια [IPPImage](../../com.aspose.slides/ippimage) στην οποία αναφέρεται. |

**Επιστρέφει:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Το νέο δημιουργημένο [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε points. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε points. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε points. |
| section | [ISection](../../com.aspose.slides/isection) | Το [ISection](../../com.aspose.slides/isection) στο οποίο αναφέρεται το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

**Επιστρέφει:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νέο δημιουργημένο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom με προκαθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε points. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε points. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε points. |
| section | [ISection](../../com.aspose.slides/isection) | Το [ISection](../../com.aspose.slides/isection) στο οποίο αναφέρεται το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η [IPPImage](../../com.aspose.slides/ippimage) που θα εμφανιστεί στο πλαίσιο Section Zoom. |

**Επιστρέφει:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νέο δημιουργημένο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το πλαίσιο Section Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε points. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε points. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε points. |
| section | [ISection](../../com.aspose.slides/isection) | Το [ISection](../../com.aspose.slides/isection) στο οποίο αναφέρεται το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

**Επιστρέφει:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νέο δημιουργημένο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο Section Zoom με προκαθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το πλαίσιο Section Zoom. |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε points. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε points. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε points. |
| section | [ISection](../../com.aspose.slides/isection) | Το [ISection](../../com.aspose.slides/isection) στο οποίο αναφέρεται το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Η εικόνα που θα εμφανιστεί στο πλαίσιο Section Zoom. |

**Επιστρέφει:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Το νέο δημιουργημένο [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει πώς να προσθέσετε ένα αντικείμενο Summary Zoom στο τέλος μιας συλλογής
>  (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαίσιου Summary Zoom, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαίσιου Summary Zoom, σε points. |
| width | float | Το πλάτος του νέου πλαίσιου Summary Zoom, σε points. |
| height | float | Το ύψος του νέου πλαίσιου Summary Zoom, σε points. |
This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**Επιστρέφει:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Το νεοδημιουργημένο [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```


Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index.

--------------------

> ```
> This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| x | float | Η x-συντεταγμένη του νέου πλαισίου Summary Zoom, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου Summary Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Summary Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Summary Zoom, σε σημεία.

--------------------

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**Επιστρέφει:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Το νεοδημιουργημένο [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```


Creates a new video frame and adds it to the end of the shape collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου video frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου video frame, σε σημεία. |
| width | float | Το πλάτος του νέου video frame, σε σημεία. |
| height | float | Το ύψος του νέου video frame, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του αρχείου βίντεο για ενσωμάτωση. |

**Επιστρέφει:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Το νεοδημιουργημένο [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```


Creates a new video frame and adds it to the end of the shape collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου video frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου video frame, σε σημεία. |
| width | float | Το πλάτος του νέου video frame, σε σημεία. |
| height | float | Το ύψος του νέου video frame, σε σημεία. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Το [IVideo](../../com.aspose.slides/ivideo) για ενσωμάτωση στο video frame. |

**Επιστρέφει:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Το νεοδημιουργημένο [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```


Creates a new video frame and inserts it into the shape collection at the specified index.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το video frame. |
| x | float | Η x-συντεταγμένη του νέου video frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου video frame, σε σημεία. |
| width | float | Το πλάτος του νέου video frame, σε σημεία. |
| height | float | Το ύψος του νέου video frame, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του αρχείου βίντεο για ενσωμάτωση. |

**Επιστρέφει:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Το νεοδημιουργημένο [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```


Creates a new audio frame linked to a CD track and adds it to the end of the shape collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου audio frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου audio frame, σε σημεία. |
| width | float | Το πλάτος του νέου audio frame, σε σημεία. |
| height | float | Το ύψος του νέου audio frame, σε σημεία. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```


Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το audio frame. |
| x | float | Η x-συντεταγμένη του νέου audio frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου audio frame, σε σημεία. |
| width | float | Το πλάτος του νέου audio frame, σε σημεία. |
| height | float | Το ύψος του νέου audio frame, σε σημεία. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```


Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου audio frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου audio frame, σε σημεία. |
| width | float | Το πλάτος του νέου audio frame, σε σημεία. |
| height | float | Το ύψος του νέου audio frame, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του εξωτερικού αρχείου ήχου για σύνδεση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```


Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το audio frame. |
| x | float | Η x-συντεταγμένη του νέου audio frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου audio frame, σε σημεία. |
| width | float | Το πλάτος του νέου audio frame, σε σημεία. |
| height | float | Το ύψος του νέου audio frame, σε σημεία. |
| fname | java.lang.String | Η διαδρομή ή το όνομα του εξωτερικού αρχείου ήχου για σύνδεση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```


Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the Presentation.Audios collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου audio frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου audio frame, σε σημεία. |
| width | float | Το πλάτος του νέου audio frame, σε σημεία. |
| height | float | Το ύψος του νέου audio frame, σε σημεία. |
| audio_stream | java.io.InputStream | Μία ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```


Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the Presentation.Audios list.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου audio frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου audio frame, σε σημεία. |
| width | float | Το πλάτος του νέου audio frame, σε σημεία. |
| height | float | Το ύψος του νέου audio frame, σε σημεία. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Μία [IAudio](../../com.aspose.slides/iaudio) παρουσία από τη συλλογή Presentation.Audios. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```


Creates a new audio frame with an embedded WAV file and inserts it into the shape collection at the specified index. The embedded audio is added to the Presentation.Audios collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το audio frame. |
| x | float | Η x-συντεταγμένη του νέου audio frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου audio frame, σε σημεία. |
| width | float | Το πλάτος του νέου audio frame, σε σημεία. |
| height | float | Το ύψος του νέου audio frame, σε σημεία. |
| audio_stream | java.io.InputStream | Μία ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```


Creates a new audio frame and inserts it into the shape collection at the specified index using an existing audio object from the Presentation.Audios list.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το audio frame. |
| x | float | Η x-συντεταγμένη του νέου audio frame, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου audio frame, σε σημεία. |
| width | float | Το πλάτος του νέου audio frame, σε σημεία. |
| height | float | Το ύψος του νέου audio frame, σε σημεία. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Μία [IAudio](../../com.aspose.slides/iaudio) παρουσία από τη συλλογή Presentation.Audios για ενσωμάτωση. |

**Επιστρέφει:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Το νεοδημιουργημένο [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```


Returns the zero-based index of the first occurrence of the specified shape in the collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Το σχήμα που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int - Ο μηδενικός δείκτης της πρώτης εμφάνισης του σχήματος στη συλλογή σ shapes αν βρεθεί· διαφορετικά, \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```


Creates and returns an array that contains all shapes.

**Επιστρέφει:**
com.aspose.slides.IShape[] - Ένας πίνακας αντικειμένων [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```


Creates and returns an array that contains all shapes in the specified range.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Ο δείκτης του πρώτου σχήματος που θα επιστραφεί. |
| count | int | Ο αριθμός των σχημάτων που θα επιστραφούν. |

**Επιστρέφει:**
com.aspose.slides.IShape[] - Ένας πίνακας αντικειμένων [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```


Moves the specified shape to a new position within the shape collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης προορισμού όπου θα τοποθετηθεί το σ shape. |
| shape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) που θα μετακινηθεί μέσα στη συλλογή. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```


Moves the specified shapes within the shape collection, placing them starting at the given index.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης προορισμού όπου θα τοποθετηθεί το πρώτο καθορισμένο σ shape· τα επόμενα σ shapes ακολουθούν με τη σειρά που παρέχονται. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Μία ή περισσότερες [IShape](../../com.aspose.slides/ishape) παρουσιές που θα μετακινηθούν μέσα στη συλλογή. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```


Creates a new auto shape with default formatting and adds it to the end of the shape collection.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Η [ShapeType](../../com.aspose.slides/shapetype) του auto shape για προσθήκη. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νέο δημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά αρχικοποιώντας το με την προεπιλεγμένη μορφοποίηση προτύπου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Το [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος προς προσθήκη. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |
| createFromTemplate | boolean | True για την εφαρμογή του προεπιλεγμένου στιλ προτύπου (απλό στυλ, κεντραρισμένο κείμενο και μη κενό όνομα) στο νέο σχήμα· false για τη δημιουργία του σχήματος με όλες τις ιδιότητες ορισμένες στις προεπιλεγμένες τους τιμές. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νέο δημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Δημιουργεί ένα νέο αυτόματο σχήμα ορθογωνίου για μαθηματικό περιεχόμενο και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νέο δημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το νέο αυτόματο σχήμα. |
| shapeType | int | Το [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος προς εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νέο δημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά αρχικοποιώντας το με την προεπιλεγμένη μορφοποίηση προτύπου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το αυτόματο σχήμα. |
| shapeType | int | Το [ShapeType](../../com.aspose.slides/shapetype) του αυτόματου σχήματος προς εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε πόντους. |
| createFromTemplate | boolean | True για την εφαρμογή του προεπιλεγμένου στιλ προτύπου (συμπεριλαμβανομένου μη κενóυ ονόματος, απλού στυλ και κεντραρισμένου κειμένου)· false για τη δημιουργία του σχήματος με όλες τις ιδιότητες στις προεπιλεγμένες τιμές. |

**Επιστρέφει:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Το νέο δημιουργημένο [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να ταιριάζει σε οποιαδήποτε σχήματα προστεθούν σε αυτήν.

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Το νέο δημιουργημένο [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Η [ISvgImage](../../com.aspose.slides/isvgimage) που περιέχει διανυσματικό περιεχόμενο προς μετατροπή σε σχήματα. |
| x | float | Η συντεταγμένη x του πλαισίου της ομάδας, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου της ομάδας, σε πόντους. |
| width | float | Το πλάτος του πλαισίου της ομάδας, σε πόντους. |
| height | float | Το ύψος του πλαισίου της ομάδας, σε πόντους. |

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Το νέο δημιουργημένο [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Δημιουργεί ένα νέο κενό σχήμα ομάδας και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να ταιριάζει σε οποιαδήποτε σχήματα προστεθούν σε αυτήν.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το σχήμα ομάδας. |

**Επιστρέφει:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Το νέο δημιουργημένο [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο σχήμα σύνδεσμου με προεπιλεγμένη μορφοποίηση προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Το [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσμου προς προσθήκη. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |

**Επιστρέφει:**
[IConnector](../../com.aspose.slides/iconnector) - Το νέο δημιουργημένο [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο σχήμα σύνδεσμου και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Το [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσμου προς δημιουργία. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |
| createFromTemplate | boolean | True για την εφαρμογή του προεπιλεγμένου στιλ προτύπου (μη κενό όνομα, απλό στυλ)· false για τη δημιουργία του σύνδεσμου με προεπιλεγμένες τιμές ιδιοτήτων. |

**Επιστρέφει:**
[IConnector](../../com.aspose.slides/iconnector) - Το νέο δημιουργημένο [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το σχήμα σύνδεσμου. |
| shapeType | int | Το [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσμου προς εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |

**Επιστρέφει:**
[IConnector](../../com.aspose.slides/iconnector) - Το νέο δημιουργημένο [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, προαιρετικά εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το σχήμα σύνδεσμου. |
| shapeType | int | Το [ShapeType](../../com.aspose.slides/shapetype) του σχήματος σύνδεσμου προς εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |
| createFromTemplate | boolean | True για την εφαρμογή του προεπιλεγμένου στιλ προτύπου (μη κενό όνομα, απλό στυλ)· false για τη δημιουργία του σύνδεσμου με προεπιλεγμένες τιμές ιδιοτήτων. |

**Επιστρέφει:**
[IConnector](../../com.aspose.slides/iconnector) - Το νέο δημιουργημένο [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
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
| x | float | Η συντεταγμένη x του πλαισίου εικόνας, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου εικόνας, σε πόντους. |
| width | float | Το πλάτος του πλαισίου εικόνας, σε πόντους. |
| height | float | Το ύψος του πλαισίου εικόνας, σε πόντους. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Το [IPPImage](../../com.aspose.slides/ippimage) που θα εμφανιστεί στο πλαίσιο εικόνας. |

**Επιστρέφει:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Το νέο δημιουργημένο [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικής βάσης δείκτης στο οποίο θα εισαχθεί το πλαίσιο εικόνας. |
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
| x | float | Η συντεταγμένη x του πλαισίου εικόνας, σε πόντους. |
| y | float | Η συντεταγμένη y του πλαισίου εικόνας, σε πόντους. |
| width | float | Το πλάτος του πλαισίου εικόνας, σε πόντους. |
| height | float | Το ύψος του πλαισίου εικόνας, σε πόντους. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Το [IPPImage](../../com.aspose.slides/ippimage) που θα εμφανιστεί στο πλαίσιο εικόνας. |

**Επιστρέφει:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Το νέο δημιουργημένο [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Δημιουργεί ένα νέο πίνακα και το προσθέτει στο τέλος της συλλογής σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πίνακα, σε πόντους. |
| y | float | Η συντεταγμένη y του πίνακα, σε πόντους. |
| columnWidths | double[] | Πίνακας τύπου double που αντιπροσωπεύει τα πλάτη των στηλών του πίνακα, σε πόντους. |
| rowHeights | double[] | Πίνακας τύπου double που αντιπροσωπεύει τα ύψη των σειρών του πίνακα, σε πόντους. |

**Επιστρέφει:**
[ITable](../../com.aspose.slides/itable) - Το νέο δημιουργημένο [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Δημιουργεί έναν νέο πίνακα και τον εισάγει στη συλλογή σχημάτων στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί ο πίνακας. |
| x | float | Η συντεταγμένη x του πίνακα, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πίνακα, σε μονάδες points. |
| columnWidths | double[] | Ένας πίνακας τύπου double που αντιπροσωπεύει τα πλάτη των στηλών του πίνακα, σε μονάδες points. |
| rowHeights | double[] | Ένας πίνακας τύπου double που αντιπροσωπεύει τα ύψη των γραμμών του πίνακα, σε μονάδες points. |

**Επιστρέφει:**
[ITable](../../com.aspose.slides/itable) - Το πρόσφατα δημιουργημένο [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το σχήμα στο καθορισμένο ευρετήριο από τη συλλογή σχημάτων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του σχήματος που θα αφαιρεθεί. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων.

**Παράμετροι:**
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

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) προς κλωνοποίηση. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο ευρετήριο. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο ευρετήριο. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Το [IShape](../../com.aspose.slides/ishape) προς κλωνοποίηση. |

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape) - Το πρόσφατα δημιουργημένο [IShape](../../com.aspose.slides/ishape).