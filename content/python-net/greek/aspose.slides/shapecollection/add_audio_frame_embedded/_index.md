---
title: add_audio_frame_embedded method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχήματος. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios.

### Επιστρέφει

Το νέο δημιουργημένο [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe).



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
| audio_stream | **io.RawIOBase** | Μια ροή εισόδου που περιέχει δεδομένα ήχου WAV προς ενσωμάτωση. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχήματος χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios.

### Επιστρέφει

Το νέο δημιουργημένο [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe).



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
| audio | [`IAudio`](/slides/python-net/el/aspose.slides/iaudio) | Μια [`IAudio`](/slides/python-net/el/aspose.slides/iaudio) παρουσία από τη συλλογή Presentation.Audios. |



### Δείτε επίσης
* κλάση [`IAudio`](/slides/python-net/el/aspose.slides/iaudio)
* κλάση [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe)
* κλάση [`ShapeCollection`](/slides/python-net/el/aspose.slides/shapecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)