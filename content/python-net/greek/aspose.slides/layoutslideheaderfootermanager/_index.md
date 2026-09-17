---
title: LayoutSlideHeaderFooterManager class
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager κλάση

Αντιπροσωπεύει διαχειριστή που διατηρεί τη συμπεριφορά του υποσέλιδου διαφάνειας διάταξης, των placeholder ημερομηνίας-ώρας, αριθμού σελίδας και όλων των παιδικών placeholder.
            Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε διαφάνειες εξαρτώμενες.
            Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης.

**Κληρονόμηση:**[`LayoutSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/el/aspose.slides/baseheaderfootermanager)

Ο τύπος LayoutSlideHeaderFooterManager εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Ιδιότητα | Περιγραφή |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/is_footer_visible/) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει placeholder υποσέλιδου.<br/>            Ανάγνωση **bool**. |
| [`is_slide_number_visible`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/is_slide_number_visible/) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει placeholder αριθμού σελίδας.<br/>            Ανάγνωση**bool**. |
| [`is_date_time_visible`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/is_date_time_visible/) | Λαμβάνει τιμή που υποδεικνύει ότι υπάρχει placeholder ημερομηνίας-ώρας.<br/>            Ανάγνωση**bool**. |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_footer_visibility/#bool) | Αλλάζει την ορατότητα του placeholder υποσέλιδου της διαφάνειας. |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_slide_number_visibility/#bool) | Αλλάζει την ορατότητα του placeholder αριθμού σελίδας της διαφάνειας. |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_date_time_visibility/#bool) | Αλλάζει την ορατότητα του placeholder ημερομηνίας-ώρας της διαφάνειας. |
| [`set_footer_text(self, text)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_footer_text/#str) | Ορίζει κείμενο στο placeholder υποσέλιδου της διαφάνειας. |
| [`set_date_time_text(self, text)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_date_time_text/#str) | Ορίζει κείμενο στο placeholder ημερομηνίας-ώρας της διαφάνειας. |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | Αλλάζει την ορατότητα του placeholder υποσέλιδου διαφάνειας διάταξης και όλων των παιδικών placeholder υποσέλιδου.<br/>            Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτώμενες διαφάνειες.<br/>            Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη κύρια διαφάνεια. |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | Αλλάζει την ορατότητα του placeholder αριθμού σελίδας διαφάνειας διάταξης και όλων των παιδικών placeholder αριθμού σελίδας.<br/>            Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτώμενες διαφάνειες.<br/>            Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | Αλλάζει την ορατότητα του placeholder ημερομηνίας-ώρας διαφάνειας διάταξης και όλων των παιδικών placeholder ημερομηνίας-ώρας.<br/>            Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτώμενες διαφάνειες.<br/>            Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_footer_and_child_footers_text/#str) | Ορίζει κείμενο στο placeholder υποσέλιδου διαφάνειας διάταξης και σε όλα τα παιδικά placeholder υποσέλιδου.<br/>            Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτώμενες διαφάνειες.<br/>            Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | Ορίζει κείμενο στο placeholder ημερομηνίας-ώρας διαφάνειας διάταξης και σε όλα τα παιδικά placeholder ημερομηνίας-ώρας.<br/>            Τα παιδικά placeholder σημαίνουν ότι τα placeholder περιλαμβάνονται σε εξαρτώμενες διαφάνειες.<br/>            Οι εξαρτώμενες διαφάνειες χρησιμοποιούν και εξαρτώνται από τη διαφάνεια διάταξης. |

### Δείτε επίσης
* κλάση [`BaseHeaderFooterManager`](/slides/python-net/el/aspose.slides/baseheaderfootermanager)
* κλάση [`BaseSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/baseslideheaderfootermanager)
* κλάση [`LayoutSlideHeaderFooterManager`](/slides/python-net/el/aspose.slides/layoutslideheaderfootermanager)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)