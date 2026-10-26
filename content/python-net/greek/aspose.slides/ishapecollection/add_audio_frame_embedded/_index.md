---
title: add_audio_frame_embedded method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχήματος. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios.

### Επιστρέφει

Το νεοδημιουργημένο [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio_stream | **io.RawIOBase** | Μία ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχήματος χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios.

### Επιστρέφει

Το νεοδημιουργημένο [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio | [`IAudio`](/slides/python-net/el/aspose.slides/iaudio) | Μία [`IAudio`](/slides/python-net/el/aspose.slides/iaudio) παρουσία από τη συλλογή Presentation.Audios. |



### Δείτε επίσης
* class [`IAudio`](/slides/python-net/el/aspose.slides/iaudio)
* class [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe)
* class [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/el/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)