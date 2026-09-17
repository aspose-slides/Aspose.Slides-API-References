---
title: MasterNotesSlideHeaderFooterManager class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager Klasse

Stellt den Manager dar, der das Verhalten des Fußzeilen-Platzhalters, des Datums-Uhrzeit-Platzhalters, des Seitenzahlen-Platzhalters und aller untergeordneten Platzhalter der Master-Notizen-Folie verwaltet.
            Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind.
            Abhängige Notizfolien verwenden und hängen von der Master-Notizen-Folie ab.

**Vererbung:**[`MasterNotesSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager) → [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/basehandoutnotesslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/de/aspose.slides/baseheaderfootermanager)

Der Typ MasterNotesSlideHeaderFooterManager stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/is_footer_visible/) | Gibt den Wert zurück, der anzeigt, dass ein Fußzeilen-Platzhalter vorhanden ist.<br/>            Lese **bool**. |
| [`is_slide_number_visible`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/is_slide_number_visible/) | Gibt den Wert zurück, der anzeigt, dass ein Seitenzahlen-Platzhalter vorhanden ist.<br/>            Lese**bool**. |
| [`is_date_time_visible`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/is_date_time_visible/) | Gibt den Wert zurück, der anzeigt, dass ein Datums-Uhrzeit-Platzhalter vorhanden ist.<br/>            Lese**bool**. |
| [`is_header_visible`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/is_header_visible/) | Gibt den Wert zurück, der anzeigt, dass ein Kopfzeilen-Platzhalter vorhanden ist.<br/>            Lese **bool**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_footer_visibility/#bool) | Ändert die Sichtbarkeit des Folienfußzeilen-Platzhalters. |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_visibility/#bool) | Ändert die Sichtbarkeit des Folienseitenzahlen-Platzhalters. |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_date_time_visibility/#bool) | Ändert die Sichtbarkeit des Foliendatums-Uhrzeit-Platzhalters. |
| [`set_footer_text(self, text)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_footer_text/#str) | Setzt Text für den Folienfußzeilen-Platzhalter. |
| [`set_date_time_text(self, text)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_date_time_text/#str) | Setzt Text für den Foliendatums-Uhrzeit-Platzhalter. |
| [`set_header_visibility(self, is_visible)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_header_visibility/#bool) | Ändert die Sichtbarkeit des Folienkopfzeilen-Platzhalters. |
| [`set_header_text(self, text)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_header_text/#str) | Setzt Text für den Folienkopfzeilen-Platzhalter. |
| [`set_header_and_child_headers_visibility(self, is_visible)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_visibility/#bool) | Ändert die Sichtbarkeit des Master-Notizen-Folien-Kopfzeilen-Platzhalters und aller zugehörigen Kopfzeilen-Platzhalter.<br/>            Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind.<br/>            Abhängige Notizfolien verwenden und hängen vom Master-Notizen-Folie ab. |
| [`set_header_and_child_headers_text(self, text)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_text/#str) | Setzt Text für den Master-Notizen-Folien-Kopfzeilen-Platzhalter und alle zugehörigen Kopfzeilen-Platzhalter.<br/>            Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind.<br/>            Abhängige Notizfolien verwenden und hängen vom Master-Notizen-Folie ab. |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | Ändert die Sichtbarkeit des Master-Folien-Fußzeilen-Platzhalters und aller zugehörigen Fußzeilen-Platzhalter.<br/>            Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind.<br/>            Abhängige Notizfolien verwenden und hängen vom Master-Notizen-Folie ab. |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | Ändert die Sichtbarkeit des Master-Folien-Seitenzahlen-Platzhalters und aller zugehörigen Seitenzahlen-Platzhalter.<br/>            Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind.<br/>            Abhängige Notizfolien verwenden und hängen vom Master-Notizen-Folie ab. |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | Ändert die Sichtbarkeit des Master-Folien-Datums-Uhrzeit-Platzhalters und aller zugehörigen Datums-Uhrzeit-Platzhalter.<br/>            Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind.<br/>            Abhängige Notizfolien verwenden und hängen vom Master-Notizen-Folie ab. |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_text/#str) | Setzt Text für den Master-Folien-Fußzeilen-Platzhalter und alle zugehörigen Fußzeilen-Platzhalter.<br/>            Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind.<br/>            Abhängige Notizfolien verwenden und hängen vom Master-Notizen-Folie ab. |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | Setzt Text für den Master-Folien-Datums-Uhrzeit-Platzhalter und alle zugehörigen Datums-Uhrzeit-Platzhalter.<br/>            Kind-Platzhalter bedeuten, dass Platzhalter auf abhängigen Notizfolien enthalten sind.<br/>            Abhängige Notizfolien verwenden und hängen vom Master-Notizen-Folie ab. |

### Siehe auch
* Klasse [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/basehandoutnotesslideheaderfootermanager)
* Klasse [`BaseHeaderFooterManager`](/slides/python-net/de/aspose.slides/baseheaderfootermanager)
* Klasse [`BaseSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/baseslideheaderfootermanager)
* Klasse [`MasterNotesSlideHeaderFooterManager`](/slides/python-net/de/aspose.slides/masternotesslideheaderfootermanager)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)