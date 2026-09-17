---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων
            στο καθορισμένο δείκτη. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios
            .

### Επιστρέφει

Το νεοδημιουργημένο [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης όπου θα εισαχθεί το πλαίσιο ήχου. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio_stream | **io.RawIOBase** | Ένα ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη
            χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios.

### Επιστρέφει

Το νεοδημιουργημένο [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης όπου θα εισαχθεί το πλαίσιο ήχου. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio | [`IAudio`](/slides/python-net/el/aspose.slides/iaudio) | Μία [`IAudio`](/slides/python-net/el/aspose.slides/iaudio) αντικείμενο από τη συλλογή Presentation.Audios για ενσωμάτωση. |



### Δείτε επίσης
* κλάση [`IAudio`](/slides/python-net/el/aspose.slides/iaudio)
* κλάση [`IAudioFrame`](/slides/python-net/el/aspose.slides/iaudioframe)
* κλάση [`ShapeCollection`](/slides/python-net/el/aspose.slides/shapecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)