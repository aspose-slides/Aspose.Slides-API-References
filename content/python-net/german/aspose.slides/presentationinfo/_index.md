---
title: PresentationInfo class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/presentationinfo/
---
## PresentationInfo Klasse

Informationen zur Präsentationsdatei

Der Typ PresentationInfo stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`is_encrypted`](/slides/python-net/de/aspose.slides/presentationinfo/is_encrypted/) | Gibt True zurück, wenn die gebundene Präsentation verschlüsselt ist, andernfalls False.<br/>            Nur lesbar **bool**. |
| [`is_password_protected`](/slides/python-net/de/aspose.slides/presentationinfo/is_password_protected/) | Gibt einen Wert zurück, der angibt, ob die gebundene Präsentation durch ein Passwort zum Öffnen geschützt ist. |
| [`is_write_protected`](/slides/python-net/de/aspose.slides/presentationinfo/is_write_protected/) | Gibt einen Wert zurück, der angibt, ob die gebundene Präsentation schreibgeschützt ist. |
| [`load_format`](/slides/python-net/de/aspose.slides/presentationinfo/load_format/) | Gibt das Format der gebundenen Präsentation zurück.<br/>            Nur lesbar [`LoadFormat`](/slides/python-net/de/aspose.slides/loadformat). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/de/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | Schreibt die gebundene Präsentation in einen Stream. |
| [`write_binded_presentation(self, file)`](/slides/python-net/de/aspose.slides/presentationinfo/write_binded_presentation/#str) | Schreibt die gebundene Präsentation in eine Datei. |
| [`check_password(self, password)`](/slides/python-net/de/aspose.slides/presentationinfo/check_password/#str) | Prüft, ob ein Passwort für eine mit einem Öffnungspasswort geschützte Präsentation korrekt ist. |
| [`check_write_protection(self, password)`](/slides/python-net/de/aspose.slides/presentationinfo/check_write_protection/#str) | Prüft, ob ein Änderungspasswort für eine schreibgeschützte Präsentation korrekt ist. |
| [`read_document_properties(self)`](/slides/python-net/de/aspose.slides/presentationinfo/read_document_properties/#) | Gibt die Dokumenteigenschaften der gebundenen Präsentation zurück. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/de/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Aktualisiert die Eigenschaften der gebundenen Präsentation. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)