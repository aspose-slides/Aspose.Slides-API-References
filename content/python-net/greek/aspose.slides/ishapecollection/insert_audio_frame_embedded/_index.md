---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios.

### Επιστρέφει

Το νεοδημιουργημένο [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο ήχου. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| audio_stream | **io.RawIOBase** | Η ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios.

### Επιστρέφει

Το νεοδημιουργημένο [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το πλαίσιο ήχου. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| audio | [`IAudio`](/slides/python-net/el/aspose.slides/iaudio) | Μια παρουσίαση [`IAudio`](/slides/python-net/el/aspose.slides/iaudio) από τη συλλογή Presentation.Audios για ενσωμάτωση. |



### Δείτε επίσης
* κλάση [`IAudio`](/slides/python-net/el/aspose.slides/iaudio)
* κλάση [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe)
* κλάση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)