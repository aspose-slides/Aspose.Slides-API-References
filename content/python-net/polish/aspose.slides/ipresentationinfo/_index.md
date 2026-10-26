---
title: IPresentationInfo class
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/ipresentationinfo/
---
## IPresentationInfo klasa

Informacje o pliku prezentacji

Typ IPresentationInfo udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`is_encrypted`](/slides/python-net/pl/aspose.slides/ipresentationinfo/is_encrypted/) | Zwraca True, jeśli powiązana prezentacja jest zaszyfrowana, w przeciwnym razie False.<br/>            Tylko do odczytu **bool**. |
| [`is_password_protected`](/slides/python-net/pl/aspose.slides/ipresentationinfo/is_password_protected/) | Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona hasłem otwarcia. |
| [`is_write_protected`](/slides/python-net/pl/aspose.slides/ipresentationinfo/is_write_protected/) | Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona przed zapisem. |
| [`load_format`](/slides/python-net/pl/aspose.slides/ipresentationinfo/load_format/) | Zwraca format powiązanej prezentacji.<br/>            Tylko do odczytu [`LoadFormat`](/slides/python-net/pl/aspose.slides/loadformat). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/pl/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Zapisuje powiązaną prezentację do strumienia. |
| [`write_binded_presentation(self, file)`](/slides/python-net/pl/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Zapisuje powiązaną prezentację do pliku. |
| [`check_password(self, password)`](/slides/python-net/pl/aspose.slides/ipresentationinfo/check_password/#str) | Sprawdza, czy hasło jest prawidłowe dla prezentacji chronionej hasłem otwarcia. |
| [`check_write_protection(self, password)`](/slides/python-net/pl/aspose.slides/ipresentationinfo/check_write_protection/#str) | Sprawdza, czy hasło do modyfikacji jest prawidłowe dla prezentacji chronionej przed zapisem. |
| [`read_document_properties(self)`](/slides/python-net/pl/aspose.slides/ipresentationinfo/read_document_properties/#) | Zwraca właściwości dokumentu powiązanej prezentacji. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/pl/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Aktualizuje właściwości powiązanej prezentacji. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)