---
title: PPImage
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/ppimage/
---
## PPImage κλάση

Αναπαριστά μια εικόνα σε μια παρουσίαση.

### dispose {#dispose}

| Name | Description |
| --- | --- |
| dispose () | Disposes object. |

 **Επιστρέφει:**
void


---


### getBinaryData {#getBinaryData}

| Name | Description |
| --- | --- |
| getBinaryData () | Επιστρέφει ένα αντίγραφο των δεδομένων μιας εικόνας. Μόνο για ανάγνωση byte[]. |

 **Επιστρέφει:**
byte


---


### getContentType {#getContentType}

| Name | Description |
| --- | --- |
| getContentType () | Επιστρέφει έναν τύπο MIME μιας εικόνας, κωδικοποιημένο στο BinaryData( #getBinaryData). Μόνο για ανάγνωση String. |

 **Επιστρέφει:**
String


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Επιστρέφει το ύψος μιας εικόνας. Μόνο για ανάγνωση int. |

 **Επιστρέφει:**
int


---


### getImage {#getImage}

| Name | Description |
| --- | --- |
| getImage () | Επιστρέφει ένα αντίγραφο μιας εικόνας. Μόνο για ανάγνωση IImage. |

 **Επιστρέφει:**
IImage


---


### getSvgImage {#getSvgImage}

| Name | Description |
| --- | --- |
| getSvgImage () | Επιστρέφει ή ορίζει το αντικείμενο ISvgImage. Η τιμή αυτή υποδεικνύει ότι η εικόνα έχει δημιουργηθεί από SVG. |

 **Επιστρέφει:**
[SvgImage](../svgimage)


---


### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth () | Επιστρέφει το πλάτος μιας εικόνας. Μόνο για ανάγνωση int. |

 **Επιστρέφει:**
int


---


### getX {#getX}

| Name | Description |
| --- | --- |
| getX () | Επιστρέφει την X-μετατόνη μιας εικόνας. Μόνο για ανάγνωση int. |

 **Επιστρέφει:**
int


---


### getY {#getY}

| Name | Description |
| --- | --- |
| getY () | Επιστρέφει την Y-μετατόνη μιας εικόνας. Μόνο για ανάγνωση int. |

 **Επιστρέφει:**
int


---


### hashCode {#hashCode}

| Name | Description |
| --- | --- |
| hashCode () | Επιστρέφει τον κωδικό κατακερματισμού μιας εικόνας. |

 **Επιστρέφει:**
int


---


### replaceImage {#replaceImage}

| Name | Description |
| --- | --- |
| replaceImage (byte[]) | Αντικαθιστά τα δεδομένα της εικόνας. |

 **Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | Τα δεδομένα της νέας εικόνας. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentNullException | Όταν η παράμετρος newImageData είναι null. |


---


### replaceImage {#replaceImage}

| Name | Description |
| --- | --- |
| replaceImage ([IImage](../iimage)) | Αντικαθιστά τα δεδομένα της εικόνας. Προσοχή: όταν το Image είναι μετααρχείο - θα γίνει rasterization. Χρησιμοποιήστε ReplaceImage(byte[]) αντί αυτού. |

 **Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| newImage | [IImage](../iimage) | Η νέα εικόνα. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentNullException | Όταν η παράμετρος newImage είναι null. |


---


### replaceImage {#replaceImage}

| Name | Description |
| --- | --- |
| replaceImage ([PPImage](../ppimage)) | Αντικαθιστά τα δεδομένα της εικόνας. |

 **Παράμετροι:**

| Name | Type | Description |
| --- | --- | --- |
| newImage | [PPImage](../ppimage) | Η νέα IPPImage. |

 **Επιστρέφει:**
void

 **Εξαίρεση**

| Σφάλμα | Συνθήκη |
| --- | --- |
| ArgumentNullException | Όταν η παράμετρος newImage είναι null. |


---


### setSvgImage {#setSvgImage}

| Name | Description |
| --- | --- |
| setSvgImage ([SvgImage](../svgimage)) | Επιστρέφει ή ορίζει το αντικείμενο ISvgImage. Η τιμή αυτή υποδεικνύει ότι η εικόνα έχει δημιουργηθεί από SVG. |

 **Επιστρέφει:**
void


---