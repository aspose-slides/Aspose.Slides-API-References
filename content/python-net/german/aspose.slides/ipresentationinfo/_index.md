---
title: IPresentationInfo class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ipresentationinfo/
---
## IPresentationInfo Klasse

Informationen zur Präsentationsdatei

Der Typ IPresentationInfo stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_encrypted`](/slides/python-net/de/aspose.slides/ipresentationinfo/is_encrypted/) | Liefert True, wenn die gebundene Präsentation verschlüsselt ist, sonst False.<br/>            Nur lesend **bool**. |
| [`is_password_protected`](/slides/python-net/de/aspose.slides/ipresentationinfo/is_password_protected/) | Liefert einen Wert, der angibt, ob die gebundene Präsentation durch ein Öffnungs-Passwort geschützt ist. |
| [`is_write_protected`](/slides/python-net/de/aspose.slides/ipresentationinfo/is_write_protected/) | Liefert einen Wert, der angibt, ob die gebundene Präsentation schreibgeschützt ist. |
| [`load_format`](/slides/python-net/de/aspose.slides/ipresentationinfo/load_format/) | Liefert das Format der gebundenen Präsentation.<br/>            Nur lesend [`LoadFormat`](/slides/python-net/de/aspose.slides/loadformat). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/de/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Schreibt die gebundene Präsentation in einen Stream. |
| [`write_binded_presentation(self, file)`](/slides/python-net/de/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Schreibt die gebundene Präsentation in eine Datei. |
| [`check_password(self, password)`](/slides/python-net/de/aspose.slides/ipresentationinfo/check_password/#str) | Prüft, ob ein Passwort für eine durch ein Öffnungs-Passwort geschützte Präsentation korrekt ist. |
| [`check_write_protection(self, password)`](/slides/python-net/de/aspose.slides/ipresentationinfo/check_write_protection/#str) | Prüft, ob ein Änderungs-Passwort für eine schreibgeschützte Präsentation korrekt ist. |
| [`read_document_properties(self)`](/slides/python-net/de/aspose.slides/ipresentationinfo/read_document_properties/#) | Liefert die Dokumenteigenschaften der gebundenen Präsentation. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/de/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Aktualisiert die Eigenschaften der gebundenen Präsentation. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)