---
title: MasterNotesSlideHeaderFooterManager class
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager κλάση

Αντιπροσωπεύει τον διαχειριστή που διατηρεί τη συμπεριφορά του υποσέλιδου διαφάνειας κύριων σημειώσεων, των αντικαταστάσεων ημερομηνίας-ώρας, αριθμού σελίδας και όλων των υπο-αντικαταστάσεων.  
Child placeholders mean placeholders are contained on depending notes slides.  
Depending notes slides use and depend on master notes slide.

**Inheritance:**[`MasterNotesSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager) → [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/basehandoutnotesslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/el/aspose.slides/baseheaderfootermanager)

Ο τύπος MasterNotesSlideHeaderFooterManager εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/is_footer_visible/) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει υποκατάσταση υποσέλιδου.<br/>            Ανάγνωση **bool**. |
| [`is_slide_number_visible`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/is_slide_number_visible/) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει υποκατάσταση αριθμού σελίδας.<br/>            Ανάγνωση**bool**. |
| [`is_date_time_visible`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/is_date_time_visible/) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει υποκατάσταση ημερομηνίας-ώρας.<br/>            Ανάγνωση**bool**. |
| [`is_header_visible`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/is_header_visible/) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει υποκατάσταση κεφαλίδας.<br/>            Ανάγνωση **bool**. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_footer_visibility/#bool) | Αλλάζει την ορατότητα της υποκατάστασης υποσέλιδου διαφάνειας. |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_visibility/#bool) | Αλλάζει την ορατότητα της υποκατάστασης αριθμού σελίδας διαφάνειας. |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_date_time_visibility/#bool) | Αλλάζει την ορατότητα της υποκατάστασης ημερομηνίας-ώρας διαφάνειας. |
| [`set_footer_text(self, text)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_footer_text/#str) | Ορίζει κείμενο στην υποκατάσταση υποσέλιδου διαφάνειας. |
| [`set_date_time_text(self, text)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_date_time_text/#str) | Ορίζει κείμενο στην υποκατάσταση ημερομηνίας-ώρας διαφάνειας. |
| [`set_header_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_header_visibility/#bool) | Αλλάζει την ορατότητα της υποκατάστασης κεφαλίδας διαφάνειας. |
| [`set_header_text(self, text)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_header_text/#str) | Ορίζει κείμενο στην υποκατάσταση κεφαλίδας διαφάνειας. |
| [`set_header_and_child_headers_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_visibility/#bool) | Αλλάζει την ορατότητα της υποκατάστασης κεφαλίδας διαφάνειας κύριων σημειώσεων και όλων των υπο-υποκαταστάσεων κεφαλίδας.<br/>            Child placeholders mean placeholders are contained on depending notes slides.<br/>            Depending notes slides use and depend on master notes slide. |
| [`set_header_and_child_headers_text(self, text)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_text/#str) | Ορίζει κείμενο στην υποκατάσταση κεφαλίδας διαφάνειας κύριων σημειώσεων και σε όλες τις υπο-υποκαταστάσεις κεφαλίδας.<br/>            Child placeholders mean placeholders are contained on depending notes slides.<br/>            Depending notes slides use and depend on master notes slide. |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | Αλλάζει την ορατότητα της υποκατάστασης υποσέλιδου κύριας διαφάνειας και όλων των υπο-υποκαταστάσεων υποσέλιδου.<br/>            Child placeholders mean placeholders are contained on depending notes slides.<br/>            Depending notes slides use and depend on master notes slide. |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | Αλλάζει την ορατότητα της υποκατάστασης αριθμού σελίδας κύριας διαφάνειας και όλων των υπο-υποκαταστάσεων αριθμού σελίδας.<br/>            Child placeholders mean placeholders are contained on depending notes slides.<br/>            Depending notes slides use and depend on master notes slide. |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | Αλλάζει την ορατότητα της υποκατάστασης ημερομηνίας-ώρας κύριας διαφάνειας και όλων των υπο-υποκαταστάσεων ημερομηνίας-ώρας.<br/>            Child placeholders mean placeholders are contained on depending notes slides.<br/>            Depending notes slides use and depend on master notes slide. |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_text/#str) | Ορίζει κείμενο στην υποκατάσταση υποσέλιδου κύριας διαφάνειας και σε όλες τις υπο-υποκαταστάσεις υποσέλιδου.<br/>            Child placeholders mean placeholders are contained on depending notes slides.<br/>            Depending notes slides use and depend on master notes slide. |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | Ορίζει κείμενο στην υποκατάσταση ημερομηνίας-ώρας κύριας διαφάνειας και σε όλες τις υπο-υποκαταστάσεις ημερομηνίας-ώρας.<br/>            Child placeholders mean placeholders are contained on depending notes slides.<br/>            Depending notes slides use and depend on master notes slide. |

### Δείτε επίσης
* κλάση [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/basehandoutnotesslideheaderfootermanager)
* κλάση [`BaseHeaderFooterManager`](/slides/python-net/el/aspose.slides/baseheaderfootermanager)
* κλάση [`BaseSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/baseslideheaderfootermanager)
* κλάση [`MasterNotesSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/masternotesslideheaderfootermanager)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)