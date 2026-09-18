---
title: PresentationInfo class
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/presentationinfo/
---
## PresentationInfo klasa

Informacje o pliku prezentacji

Typ PresentationInfo udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_encrypted`](/slides/python-net/pl/aspose.slides/presentationinfo/is_encrypted/) | Zwraca True, jeśli powiązana prezentacja jest zaszyfrowana, w przeciwnym razie False.<br/>            Read-only **bool**. |
| [`is_password_protected`](/slides/python-net/pl/aspose.slides/presentationinfo/is_password_protected/) | Zwraca wartość określającą, czy powiązana prezentacja jest chroniona hasłem do otwarcia. |
| [`is_write_protected`](/slides/python-net/pl/aspose.slides/presentationinfo/is_write_protected/) | Zwraca wartość określającą, czy powiązana prezentacja jest chroniona przed zapisem. |
| [`load_format`](/slides/python-net/pl/aspose.slides/presentationinfo/load_format/) | Zwraca format powiązanej prezentacji.<br/>            Read-only [`LoadFormat`](/slides/python-net/pl/aspose.slides/loadformat). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/pl/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | Zapisuje powiązaną prezentację do strumienia. |
| [`write_binded_presentation(self, file)`](/slides/python-net/pl/aspose.slides/presentationinfo/write_binded_presentation/#str) | Zapisuje powiązaną prezentację do pliku. |
| [`check_password(self, password)`](/slides/python-net/pl/aspose.slides/presentationinfo/check_password/#str) | Sprawdza, czy hasło jest poprawne dla prezentacji chronionej hasłem otwarcia. |
| [`check_write_protection(self, password)`](/slides/python-net/pl/aspose.slides/presentationinfo/check_write_protection/#str) | Sprawdza, czy hasło modyfikacji jest poprawne dla prezentacji chronionej przed zapisem. |
| [`read_document_properties(self)`](/slides/python-net/pl/aspose.slides/presentationinfo/read_document_properties/#) | Zwraca właściwości dokumentu powiązanej prezentacji. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/pl/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Aktualizuje właściwości powiązanej prezentacji. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)