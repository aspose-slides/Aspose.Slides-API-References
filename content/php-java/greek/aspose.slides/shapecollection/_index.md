---
title: ShapeCollection
second_title: Αναφορά API Java για Aspose.Sildes μέσω PHP
description: 
type: docs

url: /el/aspose.slides/shapecollection/
---
## ShapeCollection κλάση

 Αντιπροσωπεύει μια συλλογή σχημάτων.
 
### addAudioFrameCD {#addAudioFrameCD}

| Όνομα | Περιγραφή |
| --- | --- |
| addAudioFrameCD (float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με ένα κομμάτι CD και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |

 **Επιστρέφει:**
[AudioFrame](../audioframe)


---


### addAudioFrameEmbedded {#addAudioFrameEmbedded}

| Όνομα | Περιγραφή |
| --- | --- |
| addAudioFrameEmbedded (float, float, float, float, InputStream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio_stream | InputStream | Ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |

 **Επιστρέφει:**
[AudioFrame](../audioframe)


---


### addAudioFrameEmbedded {#addAudioFrameEmbedded}

| Όνομα | Περιγραφή |
| --- | --- |
| addAudioFrameEmbedded (float, float, float, float, [Audio](../audio)) | Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio | [Audio](../audio) | Μια παρουσία IAudio από τη συλλογή Presentation.Audios. |

 **Επιστρέφει:**
[AudioFrame](../audioframe)


---


### addAudioFrameLinked {#addAudioFrameLinked}

| Όνομα | Περιγραφή |
| --- | --- |
| addAudioFrameLinked (float, float, float, float, String) | Δημιουργεί ένα νέο πλαίσιο ήχου που συνδέεται με εξωτερικό αρχείο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η x-συντεταγμένη του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| fname | String | Η διαδρομή ή το όνομα του εξωτερικού αρχείου ήχου για σύνδεση. |

 **Επιστρέφει:**
[AudioFrame](../audioframe)


---


### addAutoShape {#addAutoShape}

| Όνομα | Περιγραφή |
| --- | --- |
| addAutoShape (int, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Ο ShapeType του αυτόματου σχήματος που θα προστεθεί. |
| x | float | Η x-συντεταγμένη του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |

 **Επιστρέφει:**
[AutoShape](../autoshape)


---


### addAutoShape {#addAutoShape}

| Όνομα | Περιγραφή |
| --- | --- |
| addAutoShape (int, float, float, float, float, boolean) | Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά αρχικοποιώντας το με προεπιλεγμένη μορφοποίηση προτύπου. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Ο ShapeType του αυτόματου σχήματος που θα προστεθεί. |
| x | float | Η x-συντεταγμένη του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |
| createFromTemplate | boolean | True για να εφαρμοστεί η προεπιλεγμένη μορφοποίηση προτύπου (απλό στυλ, κεντράρισμα κειμένου και μη κενό όνομα) στο νέο σχήμα· false για να δημιουργηθεί το σχήμα με όλες τις ιδιότητες στις προεπιλεγμένες τιμές. |

 **Επιστρέφει:**
[AutoShape](../autoshape)


---


### addChart {#addChart}

| Όνομα | Περιγραφή |
| --- | --- |
| addChart (int, float, float, float, float) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του διαγράμματος που θα προστεθεί. |
| x | float | Η x-συντεταγμένη του νέου διαγράμματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου διαγράμματος, σε σημεία. |
| width | float | Το πλάτος του διαγράμματος, σε σημεία. |
| height | float | Το ύψος του διαγράμματος, σε σημεία. |

 **Επιστρέφει:**
[Chart](../chart)


---


### addChart {#addChart}

| Όνομα | Περιγραφή |
| --- | --- |
| addChart (int, float, float, float, float, boolean) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων, και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του διαγράμματος που θα προστεθεί. |
| x | float | Η x-συντεταγμένη του νέου διαγράμματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου διαγράμματος, σε σημεία. |
| width | float | Το πλάτος του διαγράμματος, σε σημεία. |
| height | float | Το ύψος του διαγράμματος, σε σημεία. |
| initWithSample | boolean | True για να αρχικοποιηθεί το νέο διάγραμμα με δείγμα δεδομένων σειράς και ρυθμίσεων· false για να δημιουργηθεί το διάγραμμα χωρίς σειρές και μόνο με ελάχιστες ρυθμίσεις, επιταχύνοντας τη δημιουργία. |

 **Επιστρέφει:**
[Chart](../chart)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου σχήματος, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου σχήματος, σε σημεία. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Connector](../connector), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου σχήματος, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου σχήματος, σε σημεία. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Shape](../shape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου σχήματος, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου σχήματος, σε σημεία. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου σχήματος, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου σχήματος, σε σημεία. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Table](../table), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Table](../table) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου σχήματος, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου σχήματος, σε σημεία. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Ink](../ink), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου σχήματος, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου σχήματος, σε σημεία. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του νέου πλαισίου σχήματος, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου σχήματος, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου σχήματος, σε σημεία. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([GeometryShape](../geometryshape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([InkActions](../inkactions), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Chart](../chart), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του νέου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του νέου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του νέου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |
| width | float | Το πλάτος του νέου πλαισίου του σχήματος, σε points. |
| height | float | Το ύψος του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float, float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |
| width | float | Το πλάτος του νέου πλαισίου του σχήματος, σε points. |
| height | float | Το ύψος του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Connector](../connector), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Shape](../shape), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Table](../table), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Table](../table) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Ink](../ink), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([GeometryShape](../geometryshape), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([VideoFrame](../videoframe), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SmartArt](../smartart), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου του σχήματος, σε points. |
| y | float | Η συντεταγμένη y του νέου πλαισίου του σχήματος, σε points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([GroupShape](../groupshape), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου σχήματος, σε σημείο. |
| y | float | Η συντεταγμένη y του νέου πλαισίου σχήματος, σε σημείο. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([InkActions](../inkactions), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου σχήματος, σε σημείο. |
| y | float | Η συντεταγμένη y του νέου πλαισίου σχήματος, σε σημείο. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([AutoShape](../autoshape), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου σχήματος, σε σημείο. |
| y | float | Η συντεταγμένη y του νέου πλαισίου σχήματος, σε σημείο. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([PictureFrame](../pictureframe), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου σχήματος, σε σημείο. |
| y | float | Η συντεταγμένη y του νέου πλαισίου σχήματος, σε σημείο. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου σχήματος, σε σημείο. |
| y | float | Η συντεταγμένη y του νέου πλαισίου σχήματος, σε σημείο. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Chart](../chart), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου σχήματος, σε σημείο. |
| y | float | Η συντεταγμένη y του νέου πλαισίου σχήματος, σε σημείο. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([AudioFrame](../audioframe), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου σχήματος, σε σημείο. |
| y | float | Η συντεταγμένη y του νέου πλαισίου σχήματος, σε σημείο. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([ZoomObject](../zoomobject), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου σχήματος, σε σημείο. |
| y | float | Η συντεταγμένη y του νέου πλαισίου σχήματος, σε σημείο. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | Το σχήμα προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του νέου πλαισίου σχήματος, σε σημείο. |
| y | float | Η συντεταγμένη y του νέου πλαισίου σχήματος, σε σημείο. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([GraphicalObject](../graphicalobject)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήματος διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [GraphicalObject](../graphicalobject) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Connector](../connector)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήματος διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Connector](../connector) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Shape](../shape)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήματος διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Shape](../shape) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SmartArtShape](../smartartshape)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήματος διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SmartArtShape](../smartartshape) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Table](../table)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήματος διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Table](../table) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Ink](../ink)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήματος διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Ink](../ink) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SummaryZoomFrame](../summaryzoomframe)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήματος διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([GeometryShape](../geometryshape)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήματος διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [GeometryShape](../geometryshape) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SummaryZoomSection](../summaryzoomsection)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήματος διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([ZoomFrame](../zoomframe)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [ZoomFrame](../zoomframe) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([OleObjectFrame](../oleobjectframe)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([VideoFrame](../videoframe)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [VideoFrame](../videoframe) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SmartArt](../smartart)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SmartArt](../smartart) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([GroupShape](../groupshape)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [GroupShape](../groupshape) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([InkActions](../inkactions)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [InkActions](../inkactions) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([AutoShape](../autoshape)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [AutoShape](../autoshape) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([PictureFrame](../pictureframe)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [PictureFrame](../pictureframe) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([SectionZoomFrame](../sectionzoomframe)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([Chart](../chart)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [Chart](../chart) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([AudioFrame](../audioframe)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [AudioFrame](../audioframe) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([ZoomObject](../zoomobject)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [ZoomObject](../zoomobject) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addClone {#addClone}

| Όνομα | Περιγραφή |
| --- | --- |
| addClone ([LegacyDiagram](../legacydiagram)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλώνος σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [LegacyDiagram](../legacydiagram) | Το IShape προς κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### addConnector {#addConnector}

| Όνομα | Περιγραφή |
| --- | --- |
| addConnector (int, float, float, float, float) | Δημιουργεί ένα νέο σχήμα σύνδεσμου με προεπιλεγμένη μορφοποίηση προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Ο ShapeType του σχήματος σύνδεσμου που θα προστεθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε σημεία. |

**Επιστρέφει:**
[Connector](../connector)


---


### addConnector {#addConnector}

| Όνομα | Περιγραφή |
| --- | --- |
| addConnector (int, float, float, float, float, boolean) | Δημιουργεί ένα νέο σχήμα σύνδεσμου και το προσθέτει στο τέλος της συλλογής σχημάτων, εφαρμόζοντας προαιρετικά προεπιλεγμένη μορφοποίηση προτύπου. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Ο ShapeType του σχήματος σύνδεσμου που θα δημιουργηθεί. |
| x | float | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σύνδεσμου, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σύνδεσμου, σε σημεία. |
| createFromTemplate | boolean | True για εφαρμογή προεπιλεγμένης μορφοποίησης προτύπου (μη κενό όνομα, απλό στυλ); false για δημιουργία του σύνδεσμου με προεπιλεγμένες τιμές ιδιοτήτων. |

**Επιστρέφει:**
[Connector](../connector)


---


### addGroupShape {#addGroupShape}

| Όνομα | Περιγραφή |
| --- | --- |
| addGroupShape () | Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας θα προσαρμόζεται αυτόματα ώστε να περιέχει όλα τα σχήματα που προστίθενται σε αυτήν. |

**Επιστρέφει:**
[GroupShape](../groupshape)


---


### addGroupShape {#addGroupShape}

| Όνομα | Περιγραφή |
| --- | --- |
| addGroupShape ([SvgImage](../svgimage), float, float, float, float) | Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [SvgImage](../svgimage) | Το ISvgImage που περιέχει διανυσματικό περιεχόμενο για μετατροπή σε σχήματα. |
| x | float | Η συντεταγμένη x του πλαισίου της ομάδας, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου της ομάδας, σε σημεία. |
| width | float | Το πλάτος του πλαισίου της ομάδας, σε σημεία. |
| height | float | Το ύψος του πλαισίου της ομάδας, σε σημεία. |

**Επιστρέφει:**
[GroupShape](../groupshape)


---


### addMathShape {#addMathShape}

| Όνομα | Περιγραφή |
| --- | --- |
| addMathShape (float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα ορθογωνίου για την τοποθέτηση μαθηματικού περιεχομένου και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |

**Επιστρέφει:**
[AutoShape](../autoshape)


---


### addOleObjectFrame {#addOleObjectFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addOleObjectFrame (float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | Οι πληροφορίες σχετικά με τα ενσωματωμένα δεδομένα OLE ( IOleEmbeddedDataInfo). |

**Επιστρέφει:**
[OleObjectFrame](../oleobjectframe)

---


### addOleObjectFrame {#addOleObjectFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addOleObjectFrame (float, float, float, float, String, String) | Δημιουργεί ένα νέο πλαίσιο αντικειμένου OLE και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε σημεία. |
| className | String | Το όνομα κλάσης του αντικειμένου OLE. |
| path | String | Η διαδρομή προς το συνδεδεμένο αρχείο. Αυτή η διαδρομή αποθηκεύεται ακριβώς όπως είναι στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο θα είναι μη προσβάσιμο όταν ανοίγετε την παρουσίαση από διαφορετικό κατάλογο. |

**Επιστρέφει:**
[OleObjectFrame](../oleobjectframe)

---


### addPictureFrame {#addPictureFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addPictureFrame (int, float, float, float, float, [PPImage](../ppimage)) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | int | Καθορίζει τον τύπο σχήματος που περιέχεται στο ShapeType, εκτός από όλα τα είδη γραμμών: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Η συντεταγμένη x του πλαισίου εικόνας, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου εικόνας, σε σημεία. |
| width | float | Το πλάτος του πλαισίου εικόνας, σε σημεία. |
| height | float | Το ύψος του πλαισίου εικόνας, σε σημεία. |
| image | [PPImage](../ppimage) | Το IPPImage που θα εμφανιστεί στο πλαίσιο εικόνας. |

**Επιστρέφει:**
[VideoFrame](../videoframe), [PictureFrame](../pictureframe), [AudioFrame](../audioframe)

---


### addSectionZoomFrame {#addSectionZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section)) | Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε σημεία. |
| section | [Section](../section) | Το ISection στο οποίο αναφέρεται το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

**Επιστρέφει:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Σφάλμα αν το αναφερόμενο τμήμα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |

---


### addSectionZoomFrame {#addSectionZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addSectionZoomFrame (float, float, float, float, [Section](../section), [PPImage](../ppimage)) | Δημιουργεί ένα νέο πλαίσιο Section Zoom με προεπιλεγμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Section Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Section Zoom, σε σημεία. |
| section | [Section](../section) | Το ISection στο οποίο αναφέρεται το πλαίσιο Section Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [PPImage](../ppimage) | Το IPPImage που θα εμφανιστεί μέσα στο πλαίσιο Section Zoom. |

**Επιστρέφει:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Σφάλμα αν το αναφερόμενο τμήμα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |

---


### addSmartArt {#addSmartArt}

| Όνομα | Περιγραφή |
| --- | --- |
| addSmartArt (float, float, float, float, int) | Δημιουργεί ένα SmartArt διάγραμμα και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πλαισίου του διαγράμματος&#39s, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του διαγράμματος&#39s, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του διαγράμματος&#39s, σε σημεία. |
| height | float | Το ύψος του πλαισίου του διαγράμματος&#39s, σε σημεία. |
| layoutType | int | Ο τύπος διάταξης SmartArt. |

**Επιστρέφει:**
[SmartArt](../smartart)

---


### addSummaryZoomFrame {#addSummaryZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addSummaryZoomFrame (float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο Summary Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαίσιου Summary Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαίσιου Summary Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαίσιου Summary Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαίσιου Summary Zoom, σε σημεία. Αυτή η μέθοδος δημιουργεί ένα νέο Summary Zoom και βάζει μια συλλογή αντικειμένων σε αυτό για όλα τα τμήματα αυτής της παρουσίασης. |

**Επιστρέφει:**
[SummaryZoomFrame](../summaryzoomframe)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxEditException | Σφάλμα αν δεν υπάρχουν τμήματα στην παρουσίαση ή αν η στοχευόμενη διαφάνεια δεν ανήκει σε κανένα τμήμα. |

---


### addTable {#addTable}

| Όνομα | Περιγραφή |
| --- | --- |
| addTable (float, float, double[], double[]) | Δημιουργεί έναν νέο πίνακα και τον προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του πίνακα, σε σημεία. |
| y | float | Η συντεταγμένη y του πίνακα, σε σημεία. |
| columnWidths | double[] | Πίνακας διπλοτύπων που αντιπροσωπεύει τα πλάτη των στηλών του πίνακα, σε σημεία. |
| rowHeights | double[] | Πίνακας διπλοτύπων που αντιπροσωπεύει τα ύψη των γραμμών του πίνακα, σε σημεία. |

**Επιστρέφει:**
[Table](../table)

---


### addVideoFrame {#addVideoFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addVideoFrame (float, float, float, float, String) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου βίντεο, σε σημεία. |
| fname | String | Η διαδρομή ή το όνομα του αρχείου βίντεο για ενσωμάτωση. |

**Επιστρέφει:**
[VideoFrame](../videoframe)

---


### addVideoFrame {#addVideoFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addVideoFrame (float, float, float, float, [Video](../video)) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου βίντεο, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου βίντεο, σε σημεία. |
| video | [Video](../video) | Το IVideo που θα ενσωματωθεί στο πλαίσιο βίντεο. |

**Επιστρέφει:**
[VideoFrame](../videoframe)

---


### addZoomFrame {#addZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide)) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [Slide](../slide) | Το ISlide στο οποίο αναφέρεται το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |

**Επιστρέφει:**
[ZoomFrame](../zoomframe)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Σφάλμα αν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |

---


### addZoomFrame {#addZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| addZoomFrame (float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [Slide](../slide) | Το ISlide στο οποίο αναφέρεται το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |
| image | [PPImage](../ppimage) | Η εικόνα για τη διαφάνεια IPPImage. |

**Επιστρέφει:**
[ZoomFrame](../zoomframe)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Σφάλμα αν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |

---


### clear {#clear}

| Όνομα | Περιγραφή |
| --- | --- |
| clear () | Αφαιρεί όλα τα σχήματα από τη συλλογή σχημάτων. |

**Επιστρέφει:**
void

---


### getParentGroup {#getParentGroup}

| Όνομα | Περιγραφή |
| --- | --- |
| getParentGroup () | Λαμβάνει το αντικείμενο γονικού group shape για τη συλλογή σχημάτων. Μόνο για ανάγνωση IGroupShape. |

**Επιστρέφει:**
[GroupShape](../groupshape)

---


### getSyncRoot {#getSyncRoot}

| Όνομα | Περιγραφή |
| --- | --- |
| getSyncRoot () | Επιστρέφει μια ρίζα συγχρονισμού. Μόνο για ανάγνωση Object. |

**Επιστρέφει:**
Object

---


### get_Item {#get_Item}

| Όνομα | Περιγραφή |
| --- | --- |
| get_Item (int) | Λαμβάνει το στοιχείο στη συγκεκριμένη θέση. Μόνο για ανάγνωση IShape. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([GraphicalObject](../graphicalobject)) | Επιστρέφει το μηδενικής βάσης ευρετήριο της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | Το σχήμα που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int

---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([Connector](../connector)) | Επιστρέφει το μηδενικής βάσης ευρετήριο της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Connector](../connector) | Το σχήμα που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int

---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([Shape](../shape)) | Επιστρέφει το μηδενικής βάσης ευρετήριο της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../shape) | Το σχήμα που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int

---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([SmartArtShape](../smartartshape)) | Επιστρέφει το μηδενικής βάσης ευρετήριο της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | Το σχήμα που θα εντοπιστεί στη συλλογή. |

**Επιστρέφει:**
int

---


### indexOf {#indexOf}

| Όνομα | Περιγραφή |
| --- | --- |
| indexOf ([Table](../table)) | Επιστρέφει το μηδενικής βάσης ευρετήριο της πρώτης εμφάνισης του καθορισμένου σχήματος στη συλλογή. |
| shape | [Table](../table) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Ink](../ink)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Ink](../ink) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SummaryZoomFrame](../summaryzoomframe)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GeometryShape](../geometryshape)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GeometryShape](../geometryshape) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SummaryZoomSection](../summaryzoomsection)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ZoomFrame](../zoomframe)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([OleObjectFrame](../oleobjectframe)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([VideoFrame](../videoframe)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SmartArt](../smartart)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([GroupShape](../groupshape)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([InkActions](../inkactions)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [InkActions](../inkactions) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([AutoShape](../autoshape)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([PictureFrame](../pictureframe)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([SectionZoomFrame](../sectionzoomframe)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([Chart](../chart)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [Chart](../chart) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([AudioFrame](../audioframe)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([ZoomObject](../zoomobject)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf ([LegacyDiagram](../legacydiagram)) | Επιστρέφει το μηδενικό δείκτη της πρώτης εμφάνισης του καθορισμένου shape στη συλλογή. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | Το shape για εντοπισμό στη συλλογή. |

**Επιστρέφει:**
int


---


### insertAudioFrameCD {#insertAudioFrameCD}

| Name | Description |
| --- | --- |
| insertAudioFrameCD (int, float, float, float, float) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεμένο με κομμάτι CD και το εισάγει στη συλλογή shape στο καθορισμένο δείκτη. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |

**Επιστρέφει:**
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbedded {#insertAudioFrameEmbedded}

| Name | Description |
| --- | --- |
| insertAudioFrameEmbedded (int, float, float, float, float, InputStream) | Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή shape στο καθορισμένο δείκτη. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio_stream | InputStream | Ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |

**Επιστρέφει:**
[AudioFrame](../audioframe)


---


### insertAudioFrameEmbedded {#insertAudioFrameEmbedded}

| Name | Description |
| --- | --- |
| insertAudioFrameEmbedded (int, float, float, float, float, [Audio](../audio)) | Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή shape στο καθορισμένο δείκτη χρησιμοποιώντας υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio | [Audio](../audio) | Ένα αντικείμενο IAudio από τη συλλογή Presentation.Audios για ενσωμάτωση. |

**Επιστρέφει:**
[AudioFrame](../audioframe)


---


### insertAudioFrameLinked {#insertAudioFrameLinked}

| Name | Description |
| --- | --- |
| insertAudioFrameLinked (int, float, float, float, float, String) | Δημιουργεί ένα νέο πλαίσιο ήχου συνδεδεμένο με εξωτερικό αρχείο ήχου και το εισάγει στη συλλογή shape στο καθορισμένο δείκτη. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο ήχου. |
| x | float | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | float | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | float | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| fname | String | Η διαδρομή ή το όνομα του εξωτερικού αρχείου ήχου για σύνδεση. |

**Επιστρέφει:**
[AudioFrame](../audioframe)


---


### insertAutoShape {#insertAutoShape}

| Name | Description |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή shape στο καθορισμένο δείκτη, εφαρμόζοντας τη προεπιλεγμένη μορφοποίηση προτύπου. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το νέο αυτόματο σχήμα. |
| shapeType | int | Ο ShapeType του αυτόματου σχήματος προς εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |

**Επιστρέφει:**
[AutoShape](../autoshape)


---


### insertAutoShape {#insertAutoShape}

| Name | Description |
| --- | --- |
| insertAutoShape (int, int, float, float, float, float, boolean) | Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή shape στο καθορισμένο δείκτη, προαιρετικά αρχικοποιώντας το με το προεπιλεγμένο στυλ προτύπου. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το αυτόματο σχήμα. |
| shapeType | int | Ο ShapeType του αυτόματου σχήματος προς εισαγωγή. |
| x | float | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | float | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | float | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | float | Το ύψος του πλαισίου του σχήματος, σε σημεία. |
| createFromTemplate | boolean | True για εφαρμογή προεπιλεγμένου στυλ προτύπου (συμπεριλαμβανομένου μη κενό όνομα, απλό στυλ και κεντραρισμένου κειμένου); false για δημιουργία σχήματος με όλες τις ιδιότητες στα προεπιλεγμένα τους. |

**Επιστρέφει:**
[AutoShape](../autoshape)


---


### insertChart {#insertChart}

| Name | Description |
| --- | --- |
| insertChart (int, float, float, float, float, int) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το εισάγει στη συλλογή shape στο καθορισμένο δείκτη. |

**Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | Ο τύπος του διαγράμματος προς δημιουργία. |
| x | float | Η συντεταγμένη x του νέου διαγράμματος, σε σημεία. |
| y | float | Η συντεταγμένη y του νέου διαγράμματος, σε σημεία. |
| width | float | Το πλάτος του νέου διαγράμματος, σε σημεία. |
| height | float | Το ύψος του νέου διαγράμματος, σε σημεία. |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το νέο διάγραμμα στη συλλογή shape. |

**Επιστρέφει:**
[Chart](../chart)


---


### insertChart {#insertChart}

| Name | Description |
| --- | --- |
| insertChart (int, float, float, float, float, int, boolean) | Δημιουργεί ένα νέο διάγραμμα, το αρχικοποιεί με δείγμα δεδομένων σειράς και ρυθμίσεων και το εισάγει στη συλλογή shape στο καθορισμένο δείκτη. |

**Παράμετροι:**
| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | int | Ο τύπος του γραφήματος που θα δημιουργηθεί. |
| x | float | Η συντεταγμένη x του νέου γραφήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του νέου γραφήματος, σε μονάδες points. |
| width | float | Το πλάτος του νέου γραφήματος, σε μονάδες points. |
| height | float | Το ύψος του νέου γραφήματος, σε μονάδες points. |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το νέο γράφημα στη συλλογή σχημάτων. |
| initWithSample | boolean | True για την αρχικοποίηση του νέου γραφήματος με δείγμα δεδομένων σειράς και ρυθμίσεων· false για τη δημιουργία του γραφήματος χωρίς σειρές και μόνο με ελάχιστες ρυθμίσεις, κάτι που επιταχύνει τη δημιουργία. |

**Επιστρέφει:**  
[Chart](../chart)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [GraphicalObject](../graphicalobject) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Connector](../connector) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Shape](../shape) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SmartArtShape](../smartartshape) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Table](../table), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Table](../table) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Ink](../ink) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [GeometryShape](../geometryshape) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [ZoomFrame](../zoomframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δεικτής που αρχίζει από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

**Επιστρέφει:**  
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. |

**Παράμετροι:**
| sourceShape | [VideoFrame](../videoframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SmartArt](../smartart) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [GroupShape](../groupshape) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [InkActions](../inkactions), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [InkActions](../inkactions) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [AutoShape](../autoshape) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [PictureFrame](../pictureframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Chart](../chart) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [AudioFrame](../audioframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [ZoomObject](../zoomobject) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float, float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [LegacyDiagram](../legacydiagram) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | float | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | float | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [GraphicalObject](../graphicalobject) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Connector](../connector), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη καθορισμένη θέση. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης που ξεκινά από το μηδέν, στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Connector](../connector) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Shape](../shape), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Shape](../shape) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SmartArtShape](../smartartshape) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Table](../table), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Table](../table) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Ink](../ink), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Ink](../ink) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [GeometryShape](../geometryshape) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [ZoomFrame](../zoomframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [VideoFrame](../videoframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SmartArt](../smartart), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SmartArt](../smartart) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [GroupShape](../groupshape) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [InkActions](../inkactions), float, float) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [InkActions](../inkactions) | Το IShape προς κλωνοποίηση. |
| x | float | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | float | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [AutoShape](../autoshape) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [PictureFrame](../pictureframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Chart](../chart), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Chart](../chart) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [AudioFrame](../audioframe) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [ZoomObject](../zoomobject) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram), float, float) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του sourceShape. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [LegacyDiagram](../legacydiagram) | Το IShape προς κλωνοποίηση. |
| x | float | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |
| y | float | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε μονάδες points. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [GraphicalObject](../graphicalobject)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [GraphicalObject](../graphicalobject) | Το IShape προς κλωνοποίηση. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Connector](../connector)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Connector](../connector) | Το IShape προς κλωνοποίηση. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Shape](../shape)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Shape](../shape) | Το IShape προς κλωνοποίηση. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SmartArtShape](../smartartshape)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SmartArtShape](../smartartshape) | Το IShape προς κλωνοποίηση. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Table](../table)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Table](../table) | Το IShape προς κλωνοποίηση. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Ink](../ink)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Ink](../ink) | Το IShape προς κλωνοποίηση. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SummaryZoomFrame](../summaryzoomframe)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SummaryZoomFrame](../summaryzoomframe) | Το IShape προς κλωνοποίηση. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [GeometryShape](../geometryshape)) | Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού. |

 **Παράμετροι:**
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [GeometryShape](../geometryshape) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SummaryZoomSection](../summaryzoomsection)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SummaryZoomSection](../summaryzoomsection) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [ZoomFrame](../zoomframe)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [ZoomFrame](../zoomframe) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [OleObjectFrame](../oleobjectframe)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [OleObjectFrame](../oleobjectframe) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [VideoFrame](../videoframe)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [VideoFrame](../videoframe) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SmartArt](../smartart)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SmartArt](../smartart) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [GroupShape](../groupshape)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [GroupShape](../groupshape) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [InkActions](../inkactions)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [InkActions](../inkactions) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [AutoShape](../autoshape)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [AutoShape](../autoshape) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [PictureFrame](../pictureframe)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [PictureFrame](../pictureframe) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [SectionZoomFrame](../sectionzoomframe)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [SectionZoomFrame](../sectionzoomframe) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [Chart](../chart)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [Chart](../chart) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [AudioFrame](../audioframe)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [AudioFrame](../audioframe) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [ZoomObject](../zoomobject)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [ZoomObject](../zoomobject) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertClone {#insertClone}

| Όνομα | Περιγραφή |
| --- | --- |
| insertClone (int, [LegacyDiagram](../legacydiagram)) | Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού&#39s. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [LegacyDiagram](../legacydiagram) | Το IShape για κλωνοποίηση. |

**Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### insertConnector {#insertConnector}

| Όνομα | Περιγραφή |
| --- | --- |
| insertConnector (int, int, float, float, float, float) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, εφαρμόζοντας το προεπιλεγμένο στυλ πρότυπου. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το σχήμα σύνδεσης. |
| shapeType | int | Ο ShapeType του σχήματος σύνδεσης που θα εισαχθεί. |
| x | float | Η x-συντεταγμένη του πλαισίου του connector&#39s, σε μονάδες σημείου. |
| y | float | Η y-συντεταγμένη του πλαισίου του connector&#39s, σε μονάδες σημείου. |
| width | float | Το πλάτος του πλαισίου του connector&#39s, σε μονάδες σημείου. |
| height | float | Το ύψος του πλαισίου του connector&#39s, σε μονάδες σημείου. |

**Επιστρέφει:**
[Connector](../connector)


---


### insertConnector {#insertConnector}

| Όνομα | Περιγραφή |
| --- | --- |
| insertConnector (int, int, float, float, float, float, boolean) | Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, προαιρετικά εφαρμόζοντας το προεπιλεγμένο στυλ πρότυπου. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το σχήμα σύνδεσης. |
| shapeType | int | Ο ShapeType του σχήματος σύνδεσης που θα εισαχθεί. |
| x | float | Η x-συντεταγμένη του πλαισίου του connector&#39s, σε μονάδες σημείου. |
| y | float | Η y-συντεταγμένη του πλαισίου του connector&#39s, σε μονάδες σημείου. |
| width | float | Το πλάτος του πλαισίου του connector&#39s, σε μονάδες σημείου. |
| height | float | Το ύψος του πλαισίου του connector&#39s, σε μονάδες σημείου. |
| boolean | boolean | - |
| y | float | Η συντεταγμένη y του πλαισίου του connector, σε μονάδες σημείου. |
| width | float | Το πλάτος του πλαισίου του connector, σε μονάδες σημείου. |
| height | float | Το ύψος του πλαισίου του connector, σε μονάδες σημείου. |
| createFromTemplate | boolean | True για εφαρμογή προεπιλεγμένης μορφοποίησης προτύπου (μη κενό όνομα, απλό στυλ); false για δημιουργία του connector με προεπιλεγμένες τιμές ιδιοτήτων. |

**Επιστρέφει:**
[Connector](../connector)


---


### insertGroupShape {#insertGroupShape}

| Όνομα | Περιγραφή |
| --- | --- |
| insertGroupShape (int) | Δημιουργεί ένα νέο κενό group shape και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. Το πλαίσιο του group θα προσαρμόζεται αυτόματα ώστε να ταιριάζει με όλα τα shapes που προστεθούν. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το group shape. |

**Επιστρέφει:**
[GroupShape](../groupshape)


---


### insertOleObjectFrame {#insertOleObjectFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, [OleEmbeddedDataInfo](../oleembeddeddatainfo)) | Δημιουργεί ένα νέο πλαίσιο OLE object και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το πλαίσιο OLE object. |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε μονάδες σημείου. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε μονάδες σημείου. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε μονάδες σημείου. |
| dataInfo | [OleEmbeddedDataInfo](../oleembeddeddatainfo) | Οι ενσωματωμένες πληροφορίες δεδομένων OLE (IOleEmbeddedDataInfo). |

**Επιστρέφει:**
[OleObjectFrame](../oleobjectframe)


---


### insertOleObjectFrame {#insertOleObjectFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| insertOleObjectFrame (int, float, float, float, float, String, String) | Δημιουργεί ένα νέο πλαίσιο OLE object και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το πλαίσιο OLE object. |
| x | float | Η συντεταγμένη x του νέου πλαισίου OLE, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του νέου πλαισίου OLE, σε μονάδες σημείου. |
| width | float | Το πλάτος του νέου πλαισίου OLE, σε μονάδες σημείου. |
| height | float | Το ύψος του νέου πλαισίου OLE, σε μονάδες σημείου. |
| className | String | Το όνομα κλάσης του OLE object. |
| path | String | Η διαδρομή προς το συνδεδεμένο αρχείο. Αυτή η διαδρομή αποθηκεύεται ακριβώς στην παρουσίαση. Εάν καθοριστεί σχετική διαδρομή, το αρχείο θα είναι μη προσβάσιμο όταν ανοίγετε την παρουσίαση από διαφορετικό φάκελο. |

**Επιστρέφει:**
[OleObjectFrame](../oleobjectframe)


---


### insertPictureFrame {#insertPictureFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| insertPictureFrame (int, int, float, float, float, float, [PPImage](../ppimage)) | Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το πλαίσιο εικόνας. |
| shapeType | int | Καθορίζει τον τύπο σχήματος που περιέχεται στο ShapeType, εκτός από όλους τους τύπους γραμμών: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Η συντεταγμένη x του πλαισίου εικόνας, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του πλαισίου εικόνας, σε μονάδες σημείου. |
| width | float | Το πλάτος του πλαισίου εικόνας, σε μονάδες σημείου. |
| height | float | Το ύψος του πλαισίου εικόνας, σε μονάδες σημείου. |
| image | [PPImage](../ppimage) | Το IPPImage που θα εμφανιστεί στο πλαίσιο εικόνας. |

**Επιστρέφει:**
[VideoFrame](../videoframe), [PictureFrame](../pictureframe), [AudioFrame](../audioframe)


---


### insertSectionZoomFrame {#insertSectionZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section)) | Δημιουργεί ένα νέο Section Zoom πλαίσιο και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το Section Zoom πλαίσιο. |
| x | float | Η συντεταγμένη x του νέου Section Zoom πλαισίου, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του νέου Section Zoom πλαισίου, σε μονάδες σημείου. |
| width | float | Το πλάτος του νέου Section Zoom πλαισίου, σε μονάδες σημείου. |
| height | float | Το ύψος του νέου Section Zoom πλαισίου, σε μονάδες σημείου. |
| section | [Section](../section) | Το ISection που αναφέρεται από το Section Zoom πλαίσιο· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

**Επιστρέφει:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εξαίρεση εάν η αναφερόμενη ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |


---


### insertSectionZoomFrame {#insertSectionZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| insertSectionZoomFrame (int, float, float, float, float, [Section](../section), [PPImage](../ppimage)) | Δημιουργεί ένα νέο Section Zoom πλαίσιο με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το Section Zoom πλαίσιο. |
| x | float | Η συντεταγμένη x του νέου Section Zoom πλαισίου, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του νέου Section Zoom πλαισίου, σε μονάδες σημείου. |
| width | float | Το πλάτος του νέου Section Zoom πλαισίου, σε μονάδες σημείου. |
| height | float | Το ύψος του νέου Section Zoom πλαισίου, σε μονάδες σημείου. |
| section | [Section](../section) | Το ISection που αναφέρεται από το Section Zoom πλαίσιο· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [PPImage](../ppimage) | Η εικόνα που θα εμφανιστεί μέσα στο Section Zoom πλαίσιο. |

**Επιστρέφει:**
[SectionZoomFrame](../sectionzoomframe), [SummaryZoomSection](../summaryzoomsection)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εξαίρεση εάν η αναφερόμενη ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |


---


### insertSummaryZoomFrame {#insertSummaryZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| insertSummaryZoomFrame (int, float, float, float, float) | Δημιουργεί ένα νέο Summary Zoom πλαίσιο και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το Summary Zoom πλαίσιο. |
| x | float | Η συντεταγμένη x του νέου Summary Zoom πλαισίου, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του νέου Summary Zoom πλαισίου, σε μονάδες σημείου. |
| width | float | Το πλάτος του νέου Summary Zoom πλαισίου, σε μονάδες σημείου. |
| height | float | Το ύψος του νέου Summary Zoom πλαισίου, σε μονάδες σημείου. Αυτός ο τρόπος δημιουργεί ένα Summary Zoom πλαίσιο που συγκεντρώνει συνδέσμους περίληψης για όλες τις ενότητες στην παρουσίαση. |

**Επιστρέφει:**
[SummaryZoomFrame](../summaryzoomframe)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxEditException | Εξαίρεση εάν η παρουσίαση δεν περιέχει ενότητες ή εάν η διαφάνεια-στόχος δεν ανήκει σε καμία ενότητα. |


---


### insertTable {#insertTable}

| Όνομα | Περιγραφή |
| --- | --- |
| insertTable (int, float, float, double[], double[]) | Δημιουργεί έναν νέο πίνακα και τον εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί ο πίνακας. |
| x | float | Η συντεταγμένη x του πίνακα, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του πίνακα, σε μονάδες σημείου. |
| columnWidths | double[] | Ένας πίνακας double που αντιπροσωπεύει τα πλάτη των στηλών του πίνακα, σε μονάδες σημείου. |
| rowHeights | double[] | Ένας πίνακας double που αντιπροσωπεύει τα ύψη των γραμμών του πίνακα, σε μονάδες σημείου. |

**Επιστρέφει:**
[Table](../table)


---


### insertVideoFrame {#insertVideoFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| insertVideoFrame (int, float, float, float, float, String) | Δημιουργεί ένα νέο πλαίσιο βίντεο και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το πλαίσιο βίντεο. |
| x | float | Η συντεταγμένη x του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| width | float | Το πλάτος του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| height | float | Το ύψος του νέου πλαισίου βίντεο, σε μονάδες σημείου. |
| fname | String | Η διαδρομή ή το όνομα του αρχείου βίντεο που θα ενσωματωθεί. |

**Επιστρέφει:**
[VideoFrame](../videoframe)


---


### insertZoomFrame {#insertZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide)) | Δημιουργεί ένα νέο Zoom πλαίσιο και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το Zoom πλαίσιο. |
| x | float | Η συντεταγμένη x του νέου Zoom πλαισίου, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του νέου Zoom πλαισίου, σε μονάδες σημείου. |
| width | float | Το πλάτος του νέου Zoom πλαισίου, σε μονάδες σημείου. |
| height | float | Το ύψος του νέου Zoom πλαισίου, σε μονάδες σημείου. |
| slide | [Slide](../slide) | Το ISlide που αναφέρεται από το Zoom πλαίσιο. |

**Επιστρέφει:**
[ZoomFrame](../zoomframe)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εξαίρεση εάν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |


---


### insertZoomFrame {#insertZoomFrame}

| Όνομα | Περιγραφή |
| --- | --- |
| insertZoomFrame (int, float, float, float, float, [Slide](../slide), [PPImage](../ppimage)) | Δημιουργεί ένα νέο Zoom πλαίσιο με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή shape στη συγκεκριμένη θέση. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Το μηδενικό index στο οποίο θα εισαχθεί το Zoom πλαίσιο. |
| x | float | Η συντεταγμένη x του νέου Zoom πλαισίου, σε μονάδες σημείου. |
| y | float | Η συντεταγμένη y του νέου Zoom πλαισίου, σε μονάδες σημείου. |
| width | float | Το πλάτος του νέου Zoom πλαισίου, σε μονάδες σημείου. |
| height | float | Το ύψος του νέου Zoom πλαισίου, σε μονάδες σημείου. |
| slide | [Slide](../slide) | Το ISlide που αναφέρεται από το Zoom πλαίσιο. |
| image | [PPImage](../ppimage) | Η εικόνα για τη διαφάνεια-αναφορά IPPImage. |

**Επιστρέφει:**
[ZoomFrame](../zoomframe)

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| ArgumentException | Εξαίρεση εάν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |


---


### isSynchronized {#isSynchronized}

| Όνομα | Περιγραφή |
| --- | --- |
| isSynchronized () | Επιστρέφει τιμή που υποδεικνύει εάν η πρόσβαση στη συλλογή είναι συγχρονισμένη (thread-safe). Μόνο-ανάγνωση boolean. |

**Επιστρέφει:**
boolean


---


### iterator {#iterator}

| Όνομα | Περιγραφή |
| --- | --- |
| iterator () | Επιστρέφει έναν enumerator που διατρέχει τη συλλογή. |

**Επιστρέφει:**



---


### iteratorJava {#iteratorJava}

| Όνομα | Περιγραφή |
| --- | --- |
| iteratorJava () | Επιστρέφει έναν java iterator για ολόκληρη τη συλλογή. |

**Επιστρέφει:**



---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([GraphicalObject](../graphicalobject)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σ shape από τη συλλογή shape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [GraphicalObject](../graphicalobject) | Το IShape που θα αφαιρεθεί. |

**Επιστρέφει:**
void


---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([Connector](../connector)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σ shape από τη συλλογή shape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Connector](../connector) | Το IShape που θα αφαιρεθεί. |

**Επιστρέφει:**
void


---


### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([Shape](../shape)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σ shape από τη συλλογή shape. |

**Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Shape](../shape) | Το IShape που θα αφαιρεθεί. |

**Επιστρέφει:**
void


---


### remove {#remove}
| --- | --- |
| remove ([SmartArtShape](../smartartshape)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [SmartArtShape](../smartartshape) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([Table](../table)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Table](../table) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([Ink](../ink)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Ink](../ink) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([SummaryZoomFrame](../summaryzoomframe)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [SummaryZoomFrame](../summaryzoomframe) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([GeometryShape](../geometryshape)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [GeometryShape](../geometryshape) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([SummaryZoomSection](../summaryzoomsection)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [SummaryZoomSection](../summaryzoomsection) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([ZoomFrame](../zoomframe)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [ZoomFrame](../zoomframe) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([OleObjectFrame](../oleobjectframe)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [OleObjectFrame](../oleobjectframe) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([VideoFrame](../videoframe)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [VideoFrame](../videoframe) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([SmartArt](../smartart)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [SmartArt](../smartart) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([GroupShape](../groupshape)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [GroupShape](../groupshape) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([InkActions](../inkactions)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [InkActions](../inkactions) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([AutoShape](../autoshape)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [AutoShape](../autoshape) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([PictureFrame](../pictureframe)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [PictureFrame](../pictureframe) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([SectionZoomFrame](../sectionzoomframe)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [SectionZoomFrame](../sectionzoomframe) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([Chart](../chart)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [Chart](../chart) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([AudioFrame](../audioframe)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [AudioFrame](../audioframe) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([ZoomObject](../zoomobject)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [ZoomObject](../zoomobject) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove ([LegacyDiagram](../legacydiagram)) | Αφαιρεί την πρώτη εμφάνιση του καθορισμένου σχήματος από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [LegacyDiagram](../legacydiagram) | Το IShape προς αφαίρεση. |

**Returns:**
void


---

### removeAt {#removeAt}

| Όνομα | Περιγραφή |
| --- | --- |
| removeAt (int) | Αφαιρεί το σχήμα στον καθορισμένο δείκτη από τη συλλογή σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του σχήματος προς αφαίρεση. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [GraphicalObject](../graphicalobject)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [GraphicalObject](../graphicalobject) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [Connector](../connector)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [Connector](../connector) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [Shape](../shape)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [Shape](../shape) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [SmartArtShape](../smartartshape)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [SmartArtShape](../smartartshape) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [Table](../table)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [Table](../table) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [Ink](../ink)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [Ink](../ink) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [SummaryZoomFrame](../summaryzoomframe)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [SummaryZoomFrame](../summaryzoomframe) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [GeometryShape](../geometryshape)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [GeometryShape](../geometryshape) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [SummaryZoomSection](../summaryzoomsection)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [SummaryZoomSection](../summaryzoomsection) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [ZoomFrame](../zoomframe)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [ZoomFrame](../zoomframe) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [OleObjectFrame](../oleobjectframe)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [OleObjectFrame](../oleobjectframe) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [VideoFrame](../videoframe)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [VideoFrame](../videoframe) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [SmartArt](../smartart)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [SmartArt](../smartart) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [GroupShape](../groupshape)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στόχου όπου το σχήμα θα τοποθετηθεί. |
| shape | [GroupShape](../groupshape) | Το IShape προς μετακίνηση εντός της συλλογής. |

**Returns:**
void


---

### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [InkActions](../inkactions)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση εντός της συλλογής σχημάτων. |

**Parameters:**
| index | int | Ο δείκτης στόχος μηδενικής βάσης όπου το σχήμα θα τοποθετηθεί. |
| shape | [InkActions](../inkactions) | Το IShape που θα μετακινηθεί μέσα στη συλλογή. |

 **Επιστρέφει:**
void


---


### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [AutoShape](../autoshape)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης στόχος μηδενικής βάσης όπου το σχήμα θα τοποθετηθεί. |
| shape | [AutoShape](../autoshape) | Το IShape που θα μετακινηθεί μέσα στη συλλογή. |

 **Επιστρέφει:**
void


---


### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [PictureFrame](../pictureframe)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης στόχος μηδενικής βάσης όπου το σχήμα θα τοποθετηθεί. |
| shape | [PictureFrame](../pictureframe) | Το IShape που θα μετακινηθεί μέσα στη συλλογή. |

 **Επιστρέφει:**
void


---


### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [SectionZoomFrame](../sectionzoomframe)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης στόχος μηδενικής βάσης όπου το σχήμα θα τοποθετηθεί. |
| shape | [SectionZoomFrame](../sectionzoomframe) | Το IShape που θα μετακινηθεί μέσα στη συλλογή. |

 **Επιστρέφει:**
void


---


### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [Chart](../chart)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης στόχος μηδενικής βάσης όπου το σχήμα θα τοποθετηθεί. |
| shape | [Chart](../chart) | Το IShape που θα μετακινηθεί μέσα στη συλλογή. |

 **Επιστρέφει:**
void


---


### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [AudioFrame](../audioframe)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης στόχος μηδενικής βάσης όπου το σχήμα θα τοποθετηθεί. |
| shape | [AudioFrame](../audioframe) | Το IShape που θα μετακινηθεί μέσα στη συλλογή. |

 **Επιστρέφει:**
void


---


### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [ZoomObject](../zoomobject)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης στόχος μηδενικής βάσης όπου το σχήμα θα τοποθετηθεί. |
| shape | [ZoomObject](../zoomobject) | Το IShape που θα μετακινηθεί μέσα στη συλλογή. |

 **Επιστρέφει:**
void


---


### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, [LegacyDiagram](../legacydiagram)) | Μετακινεί το καθορισμένο σχήμα σε νέα θέση μέσα στη συλλογή σχημάτων. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης στόχος μηδενικής βάσης όπου το σχήμα θα τοποθετηθεί. |
| shape | [LegacyDiagram](../legacydiagram) | Το IShape που θα μετακινηθεί μέσα στη συλλογή. |

 **Επιστρέφει:**
void


---


### reorder {#reorder}

| Όνομα | Περιγραφή |
| --- | --- |
| reorder (int, com.aspose.slides.IShape[]) | Μετακινεί τα καθορισμένα σχήματα μέσα στη συλλογή σχημάτων, τοποθετώντας τα ξεκινώντας από τον δοσμένο δείκτη. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης στόχος μηδενικής βάσης όπου θα τοποθετηθεί το πρώτο καθορισμένο σχήμα· τα επόμενα σχήματα ακολουθούν με τη δοθείσα σειρά. |
| shapes | com.aspose.slides.IShape[] | Ένα ή περισσότερα αντικείμενα IShape για μετακίνηση μέσα στη συλλογή. |

 **Επιστρέφει:**
void


---


### size {#size}

| Όνομα | Περιγραφή |
| --- | --- |
| size () | Αποκτά τον αριθμό των στοιχείων που περιέχονται στην πραγματικότητα στη συλλογή. Μόνο-ανάγνωση int. |

 **Επιστρέφει:**
int


---


### toArray {#toArray}

| Όνομα | Περιγραφή |
| --- | --- |
| toArray () | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### toArray {#toArray}

| Όνομα | Περιγραφή |
| --- | --- |
| toArray (int, int) | Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στην καθορισμένη περιοχή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | int | Ο δείκτης του πρώτου σχήματος που θα επιστραφεί. |
| count | int | Ο αριθμός των σχημάτων που θα επιστραφούν. |

 **Επιστρέφει:**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)