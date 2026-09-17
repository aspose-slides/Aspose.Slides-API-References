---
title: PPImage class
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/ppimage/
---
## PPImage κλάση

Αντιπροσωπεύει μια εικόνα σε μια παρουσίαση.

Ο τύπος PPImage εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`binary_data`](/slides/python-net/el/aspose.slides/ppimage/binary_data/) | Επιστρέφει ένα αντίγραφο των δεδομένων μιας εικόνας.<br/>            Μόνο για ανάγνωση **int**[]. |
| [`image`](/slides/python-net/el/aspose.slides/ppimage/image/) | Επιστρέφει ένα αντίγραφο μιας εικόνας.<br/>            Μόνο για ανάγνωση [`IImage`](/slides/python-net/el/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/el/aspose.slides/ppimage/svg_image/) | Επιστρέφει ή ορίζει το αντικείμενο ISvgImage [`ISvgImage`](/slides/python-net/el/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/el/aspose.slides/ppimage/content_type/) | Επιστρέφει έναν τύπο MIME μιας εικόνας, κωδικοποιημένο σε [`PPImage.binary_data`](/slides/python-net/el/aspose.slides/ppimage/binary_data).<br/>            Μόνο για ανάγνωση **str**. |
| [`width`](/slides/python-net/el/aspose.slides/ppimage/width/) | Επιστρέφει το πλάτος μιας εικόνας.<br/>            Μόνο για ανάγνωση **int**. |
| [`height`](/slides/python-net/el/aspose.slides/ppimage/height/) | Επιστρέφει το ύψος μιας εικόνας.<br/>            Μόνο για ανάγνωση **int**. |
| [`x`](/slides/python-net/el/aspose.slides/ppimage/x/) | Επιστρέφει τη μετατόπιση X μιας εικόνας.<br/>            Μόνο για ανάγνωση **int**. |
| [`y`](/slides/python-net/el/aspose.slides/ppimage/y/) | Επιστρέφει τη μετατόπιση Y μιας εικόνας.<br/>            Μόνο για ανάγνωση **int**. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/el/aspose.slides/ppimage/replace_image/#bytes) | Αντικαθιστά τα δεδομένα εικόνας.<br/>            Τα νέα δεδομένα της εικόνας. Όταν η παράμετρος newImageData είναι None. |
| [`replace_image(self, new_image)`](/slides/python-net/el/aspose.slides/ppimage/replace_image/#iimage) | Αντικαθιστά τα δεδομένα της εικόνας. Προσοχή: όταν η Image είναι μετααρχείο - θα rasterize. Χρησιμοποιήστε ReplaceImage(byte[]) αντί αυτού<br/>            Η νέα εικόνα. Όταν η παράμετρος newImage είναι None. |
| [`replace_image(self, new_image)`](/slides/python-net/el/aspose.slides/ppimage/replace_image/#ippimage) | Αντικαθιστά τα δεδομένα εικόνας.<br/>            Το νέο IPPImage. Όταν η παράμετρος newImage είναι None. |

### Δείτε επίσης
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)